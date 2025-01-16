# DSP Metadata
## Experiment data
Metadata that would be required to document and allow someone to repeat any given experiment, comprising:
### [ELN Consortium](https://github.com/TheELNConsortium/TheELNFileFormat/blob/master/SPECIFICATION.md) metadata
- name
- author
- description
- date created/modified
- links/mentions
- keywords

### Additional metadata
- Sample
  - Sample location
  - Sample type (water, soil, inoculum, other)
  - Link to sample collection video
- Experimental protocol
  - Pick list of protocols + other
  - Deviations from protocol
- Standard reagents
  - Pick list of standard reagents (possibly linked to experimental protocols)
  - Deviations from standard reagents

These additional metadata may be classed as 'comment' under the [ELN Consortium](https://github.com/TheELNConsortium/TheELNFileFormat/blob/master/SPECIFICATION.md) standards

## Timestamped data
### [ELN Consortium](https://github.com/TheELNConsortium/TheELNFileFormat/blob/master/SPECIFICATION.md) metadata
- comment
- status
- step

The intention is that these could subsequently be added as graph annotations
