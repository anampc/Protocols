# Beckman Coulter RNAdvance Viral RNA Isolation

### Author
[Opentrons (verified)](https://opentrons.com/)

## Categories
* Nucleic Acid Extraction & Purification
    * Beckman Coulter RNAdvance Viral

## Description
This protocol performs viral RNA isolation on up to 96 samples using the [Beckman Coulter RNAdvance Viral RNA Isolation](https://bec-techdocs-prod.s3.us-west-2.amazonaws.com/techdoc/files/ifu/en/C58529AA.pdf?AWSAccessKeyId=ASIA2KJI7HMZR5AG5YKL&Expires=1612987252&Signature=p99wczTf2xeGX0KNJdCID8eEnsQ%3D&x-amz-security-token=IQoJb3JpZ2luX2VjELP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLXdlc3QtMiJIMEYCIQDR2md%2F2f%2BMCSekuqtRDdiMLlvFg%2BhW7IRuEOJGuDEIQgIhAIMnPtmUbfEwWVNQgd9if%2BTDzksOeR9%2Bma2D%2BHWp5LKpKtsBCKz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQAhoMNzA5MjkyNDA3NjAzIgwmyoPOH858tEZGfZMqrwFZYisUqt%2BhwV40OtXmi2laFoNj6NUmH1dMq15RXNGFdZ4xTQcExGe08eVkcGcDJSHILrTMyfuykfjf2hivLPdTdvL7RcDnhS%2FW2DRs0BrNMFIRNhfrF9M2Yox1LFn34j3eylBULFa%2BC47G1s7vaxyQRLeWfMLUOn2XivRvDZ1BLDEn7AxivwHWWYFeSrDYNuZSdcnt95zNCkKTb%2BZeVYa8%2F1EapM6H6HfNG68uuyHcMJ3bkIEGOt8BvQfDrSJhg%2BjPHESpQyuh6Iavgfe9lHfXJG1%2Ff096easvBCR0fu1q7ODcJoFC3nGzOzuFS64Hgazu88M1IAxpGlDVZtdds0rYlWV7n14eLIL%2Fg%2BnsW5sbV2gku9CjGdpHC2eiTE%2BOgrQoyCbUkIUWZAaq0kj1oDANi74CLiDmulJ9dXgxYJkY3Xq02DI9%2FGzF2MzmPFnFUBiIuOPW5NEo4sx6d93gZJfV%2F9FPaAvf41MG3TGxyNWbTFBgYYacQKa31%2B0po7%2BB14SEKOxFtlC6I00wYa8AfewR21RX%2BsSAVw%3D%3D) kit and workflow.

The protocol begins at the stage of adding binding beads to lysed samples loaded on the magnetic module in a NEST 96-deepwell plate. For reagent layout in the 2 12-channel reservoirs used in this protocol, please see "Setup" below.

For sample traceability and consistency, samples are mapped directly from the magnetic extraction plate (magnetic module, slot 6) to the elution PCR plate (temperature module, slot 1). Magnetic extraction plate well A1 is transferred to elution PCR plate A1, extraction plate well B1 to elution plate B1, ..., D2 to D2, etc.

---

![Materials Needed](https://s3.amazonaws.com/opentrons-protocol-library-website/custom-README-images/001-General+Headings/materials.png)  

To purchase tips, reagents, or pipettes, please visit our [online store](https://shop.opentrons.com/) or contact our sales team at [info@opentrons.com](mailto:info@opentrons.com)

* [Opentrons Magnetic Module GEN2](https://shop.opentrons.com/collections/hardware-modules/products/magdeck)
* [Opentrons Temperature Module GEN2](https://shop.opentrons.com/collections/hardware-modules/products/tempdeck)
* [Beckman Coulter RNAdvance Viral kit](https://www.beckman.com/reagents/genomic/rna-isolation/viral/c63510)
* [NEST 12 Well Reservoir 15 mL](https://labware.opentrons.com/nest_12_reservoir_15ml)
* [NEST 1 Well Reservoir 195 mL](https://labware.opentrons.com/nest_1_reservoir_195ml)
* [NEST 96 Well Plate 100 µL PCR Full Skirt](https://labware.opentrons.com/nest_96_wellplate_100ul_pcr_full_skirt)
* [NEST 96 Deepwell Plate 2mL](https://labware.opentrons.com/nest_96_wellplate_2ml_deep)
* [Opentrons 96 Filter Tip Rack 200 µL](https://shop.opentrons.com/collections/opentrons-tips/products/opentrons-200ul-filter-tips)

---
![Setup](https://s3.amazonaws.com/opentrons-protocol-library-website/custom-README-images/001-General+Headings/Setup.png)

* Reservoir 1: slot 2
* Reservoir 2: slot 3  
![reservoirs](https://opentrons-protocol-library-website.s3.amazonaws.com/custom-README-images/bc-rnadvance-viral/Screen+Shot+2021-02-10+at+3.48.53+PM.png)

Volumes per reservoir channel: (for 96-sample run, not including dead volume):
* Bead BBD + isopropanol solution: 9.6mL
* Wash WBE: 9.6mL
* 70% Ethanol: 9.6mL
* nuclease-free water: 3.84mL

### Robot
* [OT-2](https://opentrons.com/ot-2)

## Process
1. Select your protocol parameters.
2. Download your protocol.
3. Upload your protocol into the [OT App](https://opentrons.com/ot-app).
4. Set up your deck according to the deck map.
5. Calibrate your labware, tiprack and pipette using the OT App. For calibration tips, check out our [support article](https://support.opentrons.com/ot-2/getting-started-software-setup/deck-calibration).
6. Hit "Run".

### Additional Notes
If you have any questions about this protocol, please contact the Protocol Development Team by filling out the [Troubleshooting Survey](https://protocol-troubleshooting.paperform.co/).

###### Internal
bc-rnadvance-viral
