MetaDataWalker
Provenance & Ownership

MetaDataWalker was conceived, designed, and executed solely by the dataset owner, who is also the sole human subject captured. No third-party collectors, contractors, institutions, or external funders were involved at any stage.

Intellectual Property: All video, audio, and metadata in this dataset are the sole property of the creator. No co-ownership, institutional claim, or licensing encumbrance exists.

Subject Consent: The dataset owner is also the subject, providing explicit consent for collection, storage, and commercial licensing.

Institutional / Ethics Note: No academic, governmental, or institutional framework was involved; no ethics review was conducted or required.

Data Origin: All data was captured first-person using personal equipment. No third-party datasets or externally sourced content are included.

Compliance Notes:

EU AI Act: Buyers using this dataset to train AI models should note disclosure obligations under Article 10.

GDPR: This dataset contains health-adjacent and biometric metadata for a single identified individual; consent for commercial licensing is explicitly granted by the subject.

Expedition Overview

MetaDataWalker (MDW) is a longitudinal, first-person human dataset capturing continuous physical, cognitive, and environmental adaptation across multiple high- and mid-altitude terrains in South America. The expedition tracks a single 51-year-old physically fit human subject from the UK walking across five phases in South America, spanning four countries: Peru, Chile, Argentina, and Bolivia. Each phase lasts up to approximately six months, capturing daily locomotion, terrain interaction, environmental adaptation, and physical performance for robotics, embodied AI, and human performance research.

The dataset reflects true cross-border movement, with daily walking between camps and resupply towns (~30–75 min walk) and continuous walking between countries across phases, allowing sustained cowboy camping while maintaining structured metadata and multimodal capture.

High-intensity exercise sessions (sprints, quadrupedal locomotion, endurance bursts) are captured with external validation via tripod or third-party observer, providing precise kinetic and biomechanical reference points.

The expedition begins in the Nazca hills, Peru, moves to the Atacama hills, Chile, continues through the Puna grasslands of Argentina, and concludes in the high-altitude slopes of Cerro Chacaltaya and Sajama foothills in Bolivia. At each phase, the subject maintains cowboy camping in terrain suitable for physical testing, while ensuring access to nearby towns within walking distance for resupply, urban exposure, and optional observational segments.

Audio is captured continuously and opportunistically: spontaneous reflections during locomotion, environmental reasoning, and cognition are recorded in real-time, and augmentation occurs when required for high-value environmental, urban, or high-intensity sessions. This ensures full multimodal context for robotics, AI, and human performance analysis.

Purpose & Scope

The purpose of MDW is to create a high-fidelity, first-person longitudinal dataset documenting how the subject adapts physically and cognitively over time. Captured continuously over up to six months per phase, the dataset records daily locomotion, terrain interaction, environmental adaptation, physical performance, and real-time audio, with enhanced biomechanical validation during high-intensity exertion.

Core dimensions include:

Human locomotion and physical adaptation across varied terrain

Cognitive adaptation under fatigue, altitude, and environmental stress

Minimalist living through cowboy camping and lightweight self-sufficiency

Interaction between exertion, recovery, environment, and daily activity cycles

Optional urban segments captured only when naturally encountered

Audio augmentation and continuous multimodal capture

Kinetic and biomechanical validation during high-intensity activity via tripod or third-party capture

At its core, this dataset represents a day-in-the-life capture, continuously observed across changing internal states and external conditions.

Research Questions (Analyst-Focused)

External researchers can investigate questions such as:

How do fatigue, altitude, and terrain variability influence real-world locomotion and physical adaptation?

How does gait, posture, and movement strategy adapt across terrain and weather over time?

What patterns emerge between exertion, recovery, and subsequent performance?

How does minimalist, off-grid living affect cognitive load and resilience?

How reliably can full-body mechanics be inferred from egocentric video and audio alone?

How do short, discrete activity segments influence longer-term physical and cognitive states?

How do high-intensity movements correlate with biomechanical efficiency, injury risk, and cognitive load under real-world conditions?

Physical Locomotion & Testing

Physical movement is a core stressor and intentionally above average for the subject’s age.

Captured locomotion modes:

Walking: terrain-adaptive, incline/decline, load-bearing

Running: uneven terrain, endurance-oriented

Sprinting: short, high-intensity bursts

Quadrupedal locomotion: low-to-ground, emphasizing stability, proprioception, full-body engagement

Quadrupedal movement characteristics:

Torso held low (≈15–30 cm above ground)

Alternating diagonal and lateral limb coordination

Continuous core stabilization and balance adjustment

Deliberate pacing rather than speed optimization

High-intensity movement sessions are occasionally captured by tripod or third-party observers to provide precise kinetic and biomechanical reference points, ensuring data validity for robotics and AI modeling.

Audio notes capture real-time cognition, environmental reasoning, reflections, and optional augmentation during high-intensity, urban, or unusual environmental conditions.

Movement occurs across all weather conditions where safe and is paired with fatigue, pain, and environmental metadata.

🔬 Enhanced Validation: External Kinematic Reference

Static Tripod Shots: key terrain points for gait/posture validation

Dynamic Third-Party Shots: optional, when another observer is present without influencing subject behavior

Clips serve as calibration and biomechanical validation, not primary locomotion footage

Environment

Each phase occurs in a distinct South American environment, chosen for terrain diversity, altitude, and proximity to towns (~30–75 min walk) for resupply. Cowboy camping is maintained at each location.

Nazca hills, Peru: Warm desert terrain, hills and valleys, sandy and rocky surfaces

Atacama hills, Chile: Arid highlands, rocky slopes, loose gravel, plateau sections

Puna grasslands, Argentina: High-altitude grasslands and volcanic outcrops, uneven terrain, low shrubs

Cerro Chacaltaya & Sajama foothills, Bolivia: High-altitude slopes, rocky paths, plateaus, extreme altitude exposure

Urban exposure is captured only when naturally encountered, preserving focus on real-world adaptation in largely natural environments.

High-intensity training areas are strategically selected to enable tripod or third-party kinetic capture without interference.

Data Structure

Data is organized to capture daily activity, environmental context, physical state, and audio reflections in a structured, multimodal format.

Start-of-Day Metadata:

Phase and expedition day

Location, GPS coordinates, altitude

Terrain and elevation trends

Gear and clothing state

Physical and cognitive state: fatigue, pain, mood, alertness, stress, sleep quality

Environmental conditions: temperature, light, weather, water status

Segment Metadata:

Event triggers, segment start/end times

GPS coordinates and altitude at start/end

Terrain type, surface hazards, motion type

Gait changes, fatigue, pain

Camera height and orientation

Pack weight and clothing

Optional nutrition and hydration

Qualitative notes

Tripod / third-party capture flag for high-intensity kinetic validation

Audio augmentation flag if required

End-of-Day Metadata:

Location and GPS coordinates

Cumulative fatigue, pain, mood, alertness, stress

Environmental exposure summary

Gear condition

End-of-day reflections

Audio notes for cognition, environmental reasoning, and augmentation

All data is timestamped and linked across phases for continuous longitudinal analysis.

Metadata & Capture

Forward-facing egocentric camera captures locomotion and environment

Continuous audio capture for reflections, reasoning, and augmentation

SHA-256 hashes applied to all files for integrity and reproducibility

Structured storage in JSON/CSV formats for video, audio, and metadata

Enables:

Real-world navigation system training

Gait and posture modeling under environmental stress

Terrain-human interaction studies

Cognitive load simulation during exertion

Kinetic and biomechanical analysis of high-intensity exercise

Governance

Data reviewed daily for completeness and accuracy

Cross-phase consistency maintained for comparative analysis

Dataset structured for immediate use by robotics and embodied AI teams

All audio, video, and metadata handled with strict integrity and privacy protocols

Outcome

MDW delivers a longitudinal, multimodal, first-person dataset documenting how a physically capable human adapts cognitively and physically to new environments over five phases, each up to six months.

Intended for research on:

Locomotion modeling under real-world conditions

Embodied cognition and adaptive behavior

Human–environment interaction

Robotics and AI systems grounded in reality

Kinetic and biomechanical modeling of high-intensity exertion

Provides a unique, continuous capture of a human navigating terrain, altitude, climate, and fatigue across multiple countries while maintaining self-sufficiency and structured observation.

Contact

For access inquiries or collaboration: metadatawalker@gmail.com

