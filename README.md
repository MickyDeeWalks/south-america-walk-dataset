MetaDataWalker

Long-Horizon Egocentric Embodied Locomotion Dataset

Last updated: March 2025

TL;DR: MetaDataWalker is a single-person, fully documented, long-horizon egocentric dataset capturing continuous embodied human adaptation during a real-world expedition. Locomotion and decision-making are recorded together as terrain, environment, and internal physical state evolve. Data consists of raw, forward-facing, silent, uncompressed FHD video with consistent metadata, auditable provenance, and cryptographic integrity verification. Decision-making is captured via contemporaneous audio logs (provided as transcripts), documenting timing, rationale, and contextual triggers for robotics and AI research.

All navigation is entirely human-driven: decisions are made biologically using eyesight, environmental cues, road maps, signage, and local advice. The phone is used only to log GPS coordinates at the start and end of day and segment points, not for navigation.

This dataset intentionally focuses on depth and ecological realism of one human’s embodied experience rather than breadth across multiple subjects. Researchers should interpret findings accordingly.


Dataset Overview

MetaDataWalker captures a continuous expeditionary walk through Colombia, Ecuador, Peru, Chile, and Argentina, spanning deserts, rocky passes, rural corridors, and dense urban areas. It preserves ecological validity while supporting research into embodied systems beyond controlled lab conditions.

Walking behavior and decisions are inherently coupled. Terrain negotiation, balance maintenance, pacing, route choice, stopping, and context-driven decisions emerge as a single adaptive process. Visual and metadata modalities are maintained separately but linked, enabling multi-modal research while ensuring full auditability.

Estimated total size: ~130 GB

Format: Raw FHD video (silent), audio transcripts, screenshots with embedded GPS/altitude, structured metadata


Optimized For

Egocentric perception & navigation

Long-horizon trajectory modeling

SLAM & visual localization

Robotics terrain traversal & planning

Embodied AI & context-aware locomotion research

Embodied Adaptation & Decision Context

The dataset captures real-time adaptation in both movement and decision-making. Walking behavior evolves continuously with:

Terrain geometry & surface conditions

Environmental factors (weather, urban density, obstacles)

Internal physical state (fatigue, energy availability, heat stress)

Decisions are expressed through gait modulation, posture, path selection, and extemporaneous audio reasoning.


Decisions related to:

Route selection

Pacing & stopping

Risk tolerance

Energy management

…occur naturally in response to changing conditions. Audio transcripts document timing, speed, and rationale, providing a rich signal for modeling adaptive human behavior under dynamic physical and environmental contexts.

Relevance to Robotics & Embodied Systems

Embodied systems operate in unstructured environments where:

Terrain irregularities

Surface compliance

Traction variability

Environmental stress

…produce continuous disturbances. This dataset captures human locomotion under such conditions, including moments where balance is challenged but maintained through ongoing adaptation.


Observed behaviors include:

Minor slips & transient traction loss

Rapid foot placement & stance adjustment

Upper-body compensation & momentum regulation

Smooth gait adaptation after disturbance

These naturally occurring transitions serve as reference signals for:

Humanoid & legged robotics

Assistive mobility & prosthetics

Biomechanics & human movement modeling

Simulation & digital twins

Safety modeling


Capture Paradigm

Recording is fully context-driven with no predefined triggers. Footage is captured whenever terrain, environmental, or embodied conditions indicate relevant data.

Video clips: ~1 minute duration

Audio rationale: Recorded contemporaneously, transcribed for privacy

Screenshots: Environmental context, signs, terrain details

Vehicle-assisted/hitchhiked segments are documented for transparency and exclusion

Data Modalities
Modality	Details
Video	Raw FHD (1920×1080), silent, in-camera optimizers/HDR/stabilization disabled, forward-facing egocentric viewpoint
Audio	Decision rationale recordings; raw audio not distributed, transcripts provided
Screenshots	Environmental context, signs, terrain details; each contains embedded EXIF GPS + altitude; no text/graphics overlaid
Metadata	Structured JSON/CSV per segment (baseline + augmented fields)
GPS	Start & end coordinates per video segment; start & end of day anchors only; no navigation


GPS & Location Data

Purpose: GPS logging is used only for measurement, not navigation.

Navigation decisions are made biologically: eyesight, maps, signage, local advice

Location services active only at segment start/end points

Video clips ~1 minute → start/end coordinates reasonably approximate the path

Screenshots provide additional geo-referenced visual context

Provided Data:

Start of day: GPS coordinate + altitude

Each video segment: Start GPS + altitude, End GPS + altitude

Each audio segment: Start GPS + altitude, End GPS + altitude

Each screenshot: GPS + altitude embedded in EXIF metadata

End of day: GPS coordinate + altitude


Metadata Schema

Metadata structured in two tiers: Baseline (all segments) and Augmented (environment-specific).

Baseline Fields: DATE, EXPEDITION DAY, COUNTRY, COUNTRY DAY, REGION, NEAREST PLACE, TIMEZONE, EVENT TRIGGER, SEGMENT START/END TIME, ELEVATION TREND, TERRAIN, TEMPERATURE, INFRASTRUCTURE, SURFACE, SURFACE CONDITION, STABILITY, TRACTION, LIGHT, WEATHER, GAIT CHANGES, MOTION, FOOT PLACEMENT, HAZARDS, HEAT STRESS, WATER END, FATIGUE, PAIN/ISSUES, FOOTWEAR CONDITION, PACK WEIGHT, CAMERA HEIGHT, CAMERA ANGLE, NOTES

Augmented Fields:

Arid Zones: SAND TYPE, SURFACE STABILITY, DUST, CRACK DENSITY, VEGETATION, HEAT REFLECTION, WIND, WATER AVAILABILITY
Urban Zones: TRAFFIC DENSITY, PEDESTRIAN DENSITY, CROSSINGS, OBSTACLE TYPE, SURFACE VARIABILITY, NOISE LEVEL, LIGHTING, NAVIGATION METHOD, URBAN TYPE, SIDEWALK CONDITION


Audio & Privacy

Audio captures real-time decision rationale

Raw audio files are not distributed

Transcripts are AI-assisted (OpenAI Whisper) and manually reviewed to remove names, addresses, and third-party speech

Only transcripts released, timestamp-linked to video segments

Ethical compliance: collected in public spaces, aligned with local laws


Dataset Size

Video: ~110 GB (raw FHD, 1-min clips)

Audio transcripts: ~1 GB

Screenshots: ~15 GB (EXIF GPS + altitude)

Metadata: <1 GB JSON/CSV per segment

Total: ~130 GB


Quality Control Indicators

Disturbance-driven adaptations preserved

Non-failure stabilization sequences retained

Balance-challenging conditions captured without catastrophic falls

Continuous stabilization emphasized over post-fall recovery


Data Integrity & Provenance

Chain of Custody: capture → local device → cloud → desktop ingestion, with logs and timestamps

Field Handling & Transfer: all transfers logged, cryptographic integrity applied

Hash Verification: SHA-256 baseline checks

Segment Checks: completeness, playability, metadata alignment verified


Dataset is auditable and legally compliant, with single-person sourcing simplifying licensing and attribution. Scope is intentionally single-subject; researchers should consider this when interpreting generalization.


Subject & Safety Context

Single, consistent human subject for viewpoint stability

Movement reflects natural responses to terrain, traction, fatigue, and environmental exposure

No supports, tethers, corrective aids, or staged recovery behaviors

Safety ensured via conservative exposure limits and immediate cessation if conditions exceed safe traversal thresholds

Licensing & Access

Research / AI / robotics: free sample access for qualified researchers

Commercial use: explicit permission & licensing agreement required

Privacy: audio transcribed; raw audio not distributed; GPS limited to segment start/end and screenshot EXIF only


About / Contact

Michael Dee — one person, one phone, one continuous expedition
Contact: metadatawalker@gmail.com


Emphasizes niche value vs multi-subject academic datasets

Maintains readability, privacy, and GitHub structure
