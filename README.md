# pygdo-radio

Radio station support for PyGDO, including tools for organizing recordings of
our own shows and associated assets. This is an early module skeleton; no
streaming, recording, publishing or station integration is implemented yet.

# For Humans

## Methods (planned)

- Manage radio stations and their stream information.
- Organize recordings of own shows and associated assets such as artwork,
  jingles and show notes.
- Explore station broadcasting integrations and an audio-module signal path.

## GDTs (planned)

Station details, show metadata and asset references, with helpful tooltips.

## GDOs (planned)

Stations, shows, recordings and assets, as required by the eventual design.

# For ALs

## Methods (planned)

Reuse PyGDO audio for playback and mixing. Define station and broadcasting
adapters separately; Icecast is a possible integration, not a current feature.
Capture, storage and broadcasting must be explicitly enabled and controlled.

## Discussion

- Agree with each station on its integration, permissions and handover process.
- Obtain consent for recording participants and check rights for music and
  other assets before recording, publishing or rebroadcasting.
- Keep recordings and credentials private by default; do not commit them.

## Open questions

- Which station software and API will the first integration use?
- How should shows, recordings and assets be stored and accessed?
- How will recording and stream state be indicated to participants?
