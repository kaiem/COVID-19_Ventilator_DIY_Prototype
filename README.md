# COVID-19_Ventilator_DIY_Prototype

![Image of concept](/Diagrams/ConceptOverview.png?raw=true "Optional Title")

## Vacuum Powered Ventilator 
A COVID19 initiative, to create a prototype respirator/ventilator from basic household and 3D printed components, powered solely by a vacuum source such as a ducted vacuum system or household vacuum cleaner, and devoid of any electronic control apparatus.

## *Project Status - Proof of concept, untested*

![Image of Ventilator](/images/Ventilator_CompleteView.png?raw=true "Optional Title")
.

## Aim - Establish a baseline for assessing feasibility
To establish a baseline for assessing the feasibility and suitability of a rudimentary low cost respirator/ventilator concept, as a possible aid in alleviating critical shortages of such equipment as being experienced in the medical industry resulting from the COVID19 pandemic.
Some of the discovered techniques, and ideas may provide benefit to unrelated applications.

## Inspiration
In attempting to purchase two AMBU resuscitation bags during the COID19 pandemic, money was in due course refunded due to shortage of supply. Many open source ventilator projects attempting to fill the shortage of ventilators during the pandemic are based on mechanical automation by actuation of the basic AMBU resuscitation bag. Without supply of AMBU resuscitations bags, is there an acceptable DIY alternative?

## Objectives
- To perform the basic essential function of a medical respirator/ventilator – provide active cyclic aspiration and expiration of breathing air.
- To use only 3D printed plastic components and items obtained from household supermarket and hardware stores (readily available materials and items)
- To use benign materials - For materials in contact with breathing air supply
- To minimize the number of types of materials and items needing to be acquired
- To have low sensitivity to construction tolerances
- To provide provision for input of supplementary oxygen
- To be reliable
- To be adjustable
- To be serviceable
- To be simple to operate
- To be easily constructed
- To be devoid of any custom electronic or electrical components
- To eliminate reliance on electrical components and software
- To be low cost

## Requirements
- To deliver breathing air at a specific volume at a specific pressure followed by an adjustable duration for expiration, in a cyclic manner.
- The volume of air delivered (tidal volume) per breath cycle should be preset, adjustable and quantified.
- The pressure of air delivered in each breath cycle should be preset, adjustable and quantified.
- The duration for expiration per breath cycle should be easily adjustable.
- The energy required for operation should be supplied solely by a source of vacuum, such as from a ducted vacuum system or household vacuum cleaner.

## Challenges
- Creation of effective valve elements without the luxury of intricately molded silicon valve membranes, and/or precisely engineered metal spring components.
- Providing sealing without the luxury of precision dimensional tolerances for tight fitting self-sealing interconnecting components.
- Obtaining through household supply chains, items and materials used in transporting air which are benign or at least do not produce excessively hazardous or reactive emissions.
- Designing for safe failure modes.
- Providing sufficient usability without the use of intricate electronics and software.
- Providing effective means for monitoring of conditions and pressures without electronic sensing.



## Documentation
 - [Ventilator detailed documentation](https://github.com/kaiem/COVID-19_Ventilator_DIY_Prototype/blob/master/Doc)


## Build Files
- [BOM](https://github.com/kaiem/COVID-19_Ventilator_DIY_Prototype/blob/master/BOM)
- [STL](https://github.com/kaiem/COVID-19_Ventilator_DIY_Prototype/blob/master/STL)
- [GCODE](https://github.com/kaiem/COVID-19_Ventilator_DIY_Prototype/blob/master/gcode)


## Testing
Functional testing only has been performed. No testing whatsoever has been performed on human subjects.


## Conclusion
It was found that it is possible to create a rudimentary ventilator from readily available household items and 3D printed plastic components; however it is a much less trivial exercise than first expected. The challenges in not having access to high precision molded rubber-like flexible membrane parts for valving can be overcome albeit with an increase in complexity including a higher component count, and therefore reduced expected reliability. While the idea of using a weight on a bladder bag powered by an unregulated vacuum source in a separate air circuit was first thought and expected to give rise to an inherently safe system, in practice and after some FMEA analysis at least one potentially extreme adverse and hazardous condition was identified under component failure scenarios which could result in vacuum being transferred to the patient. Anyone embarking on utilizing this concept would be well advised to mitigate this outcome. Although the system looks simple, it is expected that a high level of familiarity, understanding and knowledge of the intricacies of this apparatus would be required in order to provide effective support to a patient, and as such may be deemed an un-user-friendly device. Additionally any non-ducted vacuum sources are typically particularly noisy, and would be best positioned in a separate room or enclosure.


## Further work
It is envisaged that another iteration of development would mitigate a critical safety issue identified, improve useablity as well as add an important mode for assisted breathing. Please refer to the relevant section in the [ventilator detailed documentation](https://github.com/kaiem/COVID-19_Ventilator_DIY_Prototype/blob/master/Doc).

Due to significant cost, time and effort involved, some fund raising is needed.


## Communication
Please provide suggestions and feedback by raising an issue or pull request.


## Sponsor or Contribute
A further iteration needs your support. Please donate or contribute. Your support will be much appreciated.


## References
Test Lung - https://medium.com/@RobertLeeRead/how-to-make-your-own-accurate-test-lungs-for-testing-emergency-ventilators-2d68fe5ac460

PEEP - https://derangedphysiology.com/main/cicm-primary-exam/required-reading/respiratory-system/Chapter%20508/methods-generating-positive

https://www.helpfulengineering.org/

https://techcrunch.com/2020/03/19/open-source-project-spins-up-3d-printed-ventilator-validation-prototype-in-just-one-week/

## Acknowledgements

https://www.instructables.com/id/The-Pandemic-Ventilator/

https://panvent.blogspot.com/2020/03/updated-bellows-style-pandemic.html

https://panvent.blogspot.com/2007/02/pandemic-ventilator-contingency.html


## Licensing
This work is licensed under Creative Commons Attribution-ShareAlike 4.0 International License.
- [(CC BY-SA 4.0)](https://creativecommons.org/licenses/by-sa/4.0/)


## Disclaimer
Presented here is a starting point for a proof of concept model, from which ideas or concepts disclosed are free for development and investigative purposes only.
No claims are made that any of the objectives or requirements as listed are desirable or if indeed they result in a solution which is suitable for human use, or if in fact the resulting prototype meets any objectives or requirements.
Anyone using this information agrees to waive any and all liability.


## Warning
A ventilator can be a hazardous device and requires appropriately medically trained and certified personnel.
This is an unproven, untested prototype with much more work required to make this device useable or acceptable for use.
