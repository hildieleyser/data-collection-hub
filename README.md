# Netholabs Data Collection Hub

https://hildieleyser.github.io/data-collection-hub/

This site is the working reference for fitting out the office as a multi camera data collection space. It holds the measured record of the five rooms and the evolving plan for where every camera goes, in one place.

## Survey drawings

Architectural drawing sheets A-01 to A-15 for the five rooms: Office (354 x 315 x 280 cm), Lab (554 x 269 x 290), Cave (460 x 915 x 290, barrel vault), Engineering (500 x 1100 x 305, brick jack arches on steel beams) and Robotics (384 x 1340 x 305, barrel vault). Each room has a dimensioned floor plan, internal elevations, and where the ceiling geometry matters a cross section and reflected ceiling plan. Room envelopes are tape measured; everything estimated from photographs is listed in the notes under each sheet. The Print / PDF button produces the full drawing set as an A4 landscape document, also downloadable here as [room-survey-drawings.pdf](room-survey-drawings.pdf).

## Camera plan

Coverage plans for the two camera types in use: the Arducam OV9782 USB colour global shutter (1280 x 800, 120 fps, about 112 x 78 degrees, best from 0.8 to 2.8 m) and the Raspberry Pi HQ camera with either the 6 mm lens (55 x 43 degrees, 2.5 to 6.5 m) or the 16 mm lens (22 x 17 degrees, 6.5 to 14 m). Each camera's covered floor area is drawn in its own colour on the room plans, with overlaps reading darker.

## 3D walkthrough

A first person model of all five rooms at surveyed dimensions, with their real vaults, glazing, materials and lighting. Every camera appears as a mount post with its 3D view frustum, floor footprint and aim marker, and selecting one opens a live preview of exactly what that camera sees through its own lens. Cameras can be edited directly: moved and aimed by clicking the floor, switched between USB and the two Pi lenses, rotated, added, hidden or deleted, per room or individually. Furniture can be toggled off to plan against the bare shell.

## How the plan stays in sync

The camera plan is a single living document across the site. The 2D coverage plans redraw automatically from the latest walkthrough layout, so the drawing sheet always matches the 3D model. Edits made in a browser are saved there as a personal draft; publishing a layout for everyone means clicking Download layout file in the walkthrough and committing the resulting [camera-layout.json](camera-layout.json) to this repository, after which every visitor sees the new plan. The currently published plan has 30 cameras across the five rooms.
