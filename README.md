# Kicad Templates

## Sources for Stackup and DRC

### OSHPark

DRC: https://docs.oshpark.com/design-tools/kicad/kicad-design-rules/
2 Layer Stackup: https://docs.oshpark.com/services/two-layer/
4 Layer Stackup: https://docs.oshpark.com/services/four-layer/
6 Layer Stackup: https://docs.oshpark.com/services/six-layer/

### JLCPCB

DRC: https://jlcpcb.com/capabilities/pcb-capabilities
4 Layer Stackup: https://jlcpcb.com/impedance

#### Note on JLCPCB DRC Annular Ring
Because of the granularity of JLCPCB capabilities, the annular thickness needed to be reduced to 0.075mm to account for min via annular ring size, while the actual PTH min annular size is 0.3mm. This was chosen because there is more provided detail on the via annular size than on the actual annular size spec.
