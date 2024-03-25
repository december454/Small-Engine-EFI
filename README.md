# Small Gasoline Engine Electronic Fuel Injection System
## Quick Links
- [System Diagram](https://github.com/december454/Small-Engine-EFI/blob/main/Presentation/Microcontroller%20Engine%20EFI%20-%20System%20Diagram.png)
- [Poster Presentation - GPHC 2024](https://github.com/december454/Small-Engine-EFI/blob/main/Presentation/GPHC%202024%20-%20Electronic%20Fuel%20Injection%20-%20Poster%20Final%20(Revised).pptx)  
- [Photo Gallery](https://drive.google.com/drive/folders/1-K8DigQq3OUXWPAcYcIx51TK-QRiQJsa)
- [Test Run Videos](https://drive.google.com/drive/folders/1xPUE9m4CGjODswX5AoU1LcMaCgBp79RX)

## Abstract
Most modern internal combustion engines feature electronic fuel injection (EFI). EFI is a form of computerized engine control which regulates the amount of fuel supplied to an engine. This technology is quite prevalent in both automotive and industrial engines; however, it is still relatively uncommon on small engines (simple low-power engines, often used to power lawn mowers, generators, snow blowers, etc.). 

These small engines often utilize a carburetor, a simple purely-mechanical device which regulates the amount of fuel supplied to an engine. Carburetors are robust and cost-effective; however, they have many disadvantages when compared to an EFI system. Carburetors cannot account for dynamic environmental conditions such as ambient temperature, engine temperature, and elevation / barometric pressure. They often perform poorly whenever the engine is not at proper operating temperature, particularly during initial engine startup. They lack any feedback system (ie. Oxygen sensor) and are unable to make adjustments based on the engine’s air-fuel ratio and overall performance. In theory, an engine with a carburetor will perform worse and less efficiently than a comparable engine with EFI.

My project aims to illustrate these claims. I will implement an electronic fuel injection system on a small gasoline engine, replacing its existing carburetor and seeing if there are tangible performance improvements brought about by EFI. Furthermore, this project will illustrate the technical challenges involved in implementing a custom EFI system and explain the theory behind EFI operation.

## Engine Tuning Info
- [TunerStudio Project Folder](https://github.com/december454/Small-Engine-EFI/tree/main/Tuning/Speeduino%20Test)
- [TunerStudio Tune File](https://github.com/december454/Small-Engine-EFI/blob/main/Tuning/Speeduino%20Test/CurrentTune.msq)

## Experiment Results
- [Raw Data](https://github.com/december454/Small-Engine-EFI/tree/main/Experiment%20Trials)
### Carburetor
- [Carb - No Load (Idle)](https://github.com/december454/Small-Engine-EFI/blob/main/Experiment%20Trials/Carb%20-%20No%20Load/Summary%20-%20Carburetor%20-%20No%20Load.xlsx)
- [Carb - 1500 Watt Load](https://github.com/december454/Small-Engine-EFI/blob/main/Experiment%20Trials/Carb%20-%201500W%20Load/Summary%20-%20Carburetor%20-%201500W%20Load.xlsx)
### Electronic Fuel Injection
- [EFI - No Load (Idle)](https://github.com/december454/Small-Engine-EFI/blob/main/Experiment%20Trials/EFI%20-%20No%20Load/Summary%20-%20EFI-%20No%20Load.xlsx)
- [EFI - 1500 Watt Load](https://github.com/december454/Small-Engine-EFI/blob/main/Experiment%20Trials/EFI%20-%201500W%20Load/Summary%20-%20EFI%20-%201500W%20Load.xlsx)
