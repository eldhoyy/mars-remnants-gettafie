# Detailed Project Description

## Problem statement

Mars missions leave behind components that were essential to reaching the surface but are less visible in public storytelling than the rover itself. Their engineering roles and documented locations are spread across mission material, making the complete landing story harder for learners to understand.

## Motivation

A successful landing is a sequence of carefully engineered systems. MARS REMNANTS treats the landing hardware as part of the history of exploration and makes those systems understandable through a focused case study of the Mars 2020 Perseverance landing at Jezero Crater.

## Proposed solution

An interactive educational website that connects a NASA orbital image of the landing site with component profiles, a landing timeline, engineering explanations and a short knowledge check.

## How it works

Visitors browse four labelled records: parachute and backshell, heat shield, powered descent stage, and Perseverance rover. Each record explains purpose, engineering role and post-separation status. The rover is explicitly identified as the mission payload, not discarded landing debris. Filters group entry/protection and descent/landing systems. Timeline controls walk through entry, parachute deployment, heat-shield jettison, powered descent and touchdown. NASA references are provided alongside the stories.

## Main features

- Responsive Mars-inspired landing page and navigation.
- Interactive hardware cards with filters and detail panels.
- NASA annotated orbital landing-site image with attribution.
- Five-stage landing sequence timeline.
- Engineering explainers for thermal protection, parachute drag and sky-crane descent.
- Short interactive knowledge check.
- NASA source list and independent-project disclaimer.

## Target audience

School-age learners, teachers, university students, researchers and space enthusiasts.

## Technology stack and implementation

The front end uses semantic HTML, CSS Grid/Flexbox, responsive media queries and vanilla JavaScript. Hardware records and timeline steps are held in JavaScript data structures; click handlers update the detail panel, filters, timeline and quiz feedback. NASA imagery is embedded from its source URL. The site is static and requires no backend, account or build process.

## Creativity and innovation

Instead of treating landing debris as a list of trivia, the project frames the landing site as an engineering field archive. It distinguishes payload from discarded hardware and links each explanation to NASA evidence.

## Scientific relevance and validity

The case study uses NASA/JPL mission documentation and the NASA PIA24333 orbital view. The site avoids inventing precise coordinates and explains relative locations only where the annotated NASA image supports them. NASA source pages are linked for further learning. Challenge-specific Resources-tab eligibility must be separately confirmed before making a Global Award compliance claim.

## Expected impact

The experience can help learners understand entry, descent and landing as a connected engineering system, encourage source-based exploration and preserve interest in the history of robotic Mars exploration.

## Limitations

This first release focuses on the Mars 2020 Perseverance landing site rather than cataloguing all Mars missions. It does not provide precise coordinates for every artifact, 3D terrain navigation or a downloadable geospatial dataset. The NASA orbital image is external and requires an internet connection.

## Future development

Possible extensions include additional documented Mars missions, a geospatial map with verified coordinates, high-resolution annotated imagery, multilingual explanations, educator activities and a searchable mission-hardware catalogue.