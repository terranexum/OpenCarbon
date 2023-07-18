# OpenCarbon
Contributors: Shrila Esturi, Dahl Winters

This repository contains our emissions reduction technologies and plans, primarily for carbon but all abundant greenhouse gases (especially CH4 and N2O) should ideally be covered as we get to these.

We have three projects under OpenCarbon:
* Cyan v.2 - upgrading the Cyan v.1, a tabletop direct air capture/carbon mineralization device supported by the OpenAir Collective, to add both sorbent regeneration and renewable energy capacity.
*   [Research Articles](https://docs.google.com/document/d/1tiNw1ULPi5LnnHzu8MfO191W7D0tvZT35omd1AGcuAg/edit?pli=1)
*   [Carbon Dioxide Efficiency Notes](https://docs.google.com/document/d/16Pm9bBRxzdapvCSMIK7pCczLLNHudUFGCbRwa-fBg48/edit?usp=sharing) 
* CarbonWall - heat and acoustic insulation for interior or exterior walls to achieve greater energy efficiency and thus savings on energy bills. Our plan to get to market to sustain our contributors: [Project Plan](https://github.com/terranexum/OpenCarbon/blob/main/Project_Plan.md).
* BioDAC - a patent-free, open-sourced nontoxic functionalized biochar sorbent for direct air capture.


If the following work is of value to you, please consider supporting our work or joining as a Core Contributor through [Open Collective](https://opencollective.com/terranexum/projects/opencarbon). 

Our goal is for our Core Contributors to each earn an equal share of 50% of the proceeds we receive from OpenCarbon products that get to market to get emissions reduced. Sustainability is not just for the planet, it has to be for people too.

## Project Scope
![TerraNexum - Business Flow Model - OpenCarbon](https://github.com/terranexum/OpenCarbon/assets/20586685/f5bca265-7dc6-47f6-8599-8b5e5cd91e10)

## Product Development Areas

### CarbonWall
Heat and acoustic insulation for interior or exterior walls to achieve greater energy efficiency and thus savings on energy bills. Please find our [Project Plan](https://github.com/terranexum/OpenCarbon/blob/main/Project_Plan.md) here.

Primary ingredients: biochar and calcium carbonate, both being among the most durable storage forms of CO2 sequestration possible. The biochar will be locally sourced from properties that desire fire mitigation, particularly along roadways to allow for safe egress in the event of a wildfire. The costs of tree cutting, chipping, and transportation to a local biochar production site will be reimbursed from the proceeds of CarbonWall sales, thus we will need to define a project area and ensure we have sufficient biochar and/or calcium carbonate tonnage to make enough CarbonWall panels at a competitive price point.

Commercial and industrial building owners can receive 100% private financing through PACE (Property Assessed Clean Energy) programs in 39 states for energy efficiency upgrades, which includes building insulation. We can assist directly with Colorado-based projects but will need help coordinating projects in other states.

Ideally, residents in a county (for example, Clear Creek County here in Colorado) can have a means to pay for the community service of fire mitigating their properties while also ensuring that the carbon from the cut trees does not re-enter the atmosphere after being cut and chipped. Leaving chips on site from cut trees creates more of a fire hazard on the ground than before. 

Turning these chips into biochar uses only about 16% on average of the chips themselves to provide fuel for their own processing under low-oxygen conditions (pyrolysis). The chips are not burned, but carbonized, into a long-duration carbon storage form able to remain intact for millennia.

With sufficient tonnage resulting from wildfire mitigation efforts, it may be possible for the biochar processing company to qualify for federal 45Q carbon sequestration credits. Commercial and industrial building owners can qualify for a 30% federal investment tax credit for getting CarbonWalls installed, and with PACE financing, they have to pay nothing up front. Our CarbonWall sales can then be used to reimburse homeowners for their fire mitigation expenses. 

### BioDAC - Direct Air Capture through Functionalized Biochar

#### The State of the Art in Direct Air Capture

At present, DAC uses too much energy, and too much of that is still emissions-producing energy, for it to scale fast enough to remove even the hard-to-abate share (around 10%) of overall carbon emissions in the atmosphere.

This 13-page free report offers a comprehensive list of DAC technologies today, and how energy needs, environmental impacts, and costs can be reduced.

![image](https://user-images.githubusercontent.com/20586685/236316628-0079cb8d-8b85-47cd-ba65-95291c1f780d.png)

#### Innovating Low-Cost, Non-Toxic, Carbon-Storing Sorbents for Direct Air Capture

We also have a four-page report mentioned at the end of the above report that outlines the following sections:

1. Quaternary Ammonium (QA) Based Sorbents for Reducing Energy Consumption, Environmental Impact, and Cost
2. Using a Cellulose Backbone
3. Using a Biochar Backbone
4. Protocol for QA-Functionalized Biochar for CO2 Adsorption

![image](https://user-images.githubusercontent.com/20586685/236316734-61be3bbc-fe98-425b-bca7-7fbd345a08b7.png)

To receive a copy of this report, which contains original research and guidance to advance carbon removal, we ask for a contribution to aid our future R&D, which can be made from our [OpenCollective](https://opencollective.com/terranexum/projects/opencarbon) page.

### Cyan v.2 with the OpenAir Collective

This summer we have plans to update Cyan (OSHWA's first certified open hardware carbon removal device) to achieve true carbon negativity, given the still low availability of low-carbon calcium hydroxide and the inefficiencies in regenerating it. 

We may design 3D printed molds that can be reused to pour multiple forms, so that Cyan containers can be easily built up from individual parts able to be sourced locally without the time or emissions of waiting for transportation.

The candidate process we will be testing for Cyan v.2:

#### CO2 Capture using Fine Calcium Hydroxide
Ca(OH)2 (s) + CO2 (g) + humid air → CaCO3 (s) + H2O (l)

This is the basic chemistry of Cyan v.1. Dust and eye/skin contact must always be avoided. Use appropriate PPE until  your Ca(OH)2 is confined in a closed container.

#### CO2 Release by Rapid Reaction with HCl
2 HCl (aq) + CaCO3 (s) → CaCl2 (aq) + H2O (l) + CO2 (g)

For safety, the weakest possible solution of HCl should be used that will fully dissolve the calcium carbonate.

#### Regeneration of Fine Calcium Hydroxide and Production of Iron(III) Chloride by Combining Calcium Chloride with Rust
CaCl2 (aq) + Fe2O3 (s) → Ca(OH)2 (s) + 2FeCl3 (aq)

This is basically ice melt + rust, but both may have many impurities if you're starting here instead of at Step 1 unless you find clean sources of calcium chloride and iron(III) oxide.

#### Regeneration of HCl and Production of Iron Metal by Electrowinning Iron(III) Chloride (requires renewable electricity)
Cathode: Fe deposition, Anode (Pt or Ti required): HCl (aq) production

To get HCl (aq) and not Cl2 (g), the following are required: high Cl- concentration, high current density, low potential, low temp, slightly alkaline pH (via a suitable buffer or just more OH- ions)
