# Simulation-of-isomerization-of--Butane
System of equations: 7 unknowns, 6 fundamental equations for a batch reactor, solve for time to fully react, track reactor temperature, conversion of feedstock to product, 

University of Wisconsin – Stevens Point
PSEN 460 -PROCESS DYNAMICS AND CONTROL
Isomerization of n-butane
Designed by:
Lakari Autumn
Lamoureux Tim
Lampshire Mike
Thompson Alex
Submitted On: 10/14/2022

Table of Contents 
Introduction .........................................................3
Purpose ..............................................................4
Risk Assessment ......................................................4
What If List:.........................................................4
Data Collection.......................................................5
Assumptions: .........................................................5
Derivations of Differential Equations ................................6
DOF Analysis..........................................................8
Overall heat transfer coefficient ....................................9
Figures...............................................................10
Results and Discussion ...............................................13
Conclusion............................................................13
Works Cited...........................................................15
Appendix .............................................................16

Introduction 
It is an isomer of normal butane, and is classified as a liquified petroleum gas, as 
is butane and propane. With a tertiary carbon atom, it is the simplest alkane. Isobutane 
impacts everyday life seeing that its main functions are of a gasoline additive, a 
refrigerant, a propellent for aerosol products, and a few more.

For low temperature processes of n-butane, it is mixed with hydrogen and passed 
to a reactor around 110–171 degrees Celsius and 200-300 psi. Following that, in a highpressure separator, Hydrogen is flashed off and the hydrogen chloride is removed in a 
stripper column. The resulting mixture consists of n-butane and isobutane which are 
then sent to a fractionator to be separated. 

In industry, the main application of isobutane is in refineries as a gasoline 
additive. It is used to make a high-octane gasoline, rating 100 points on the octane 
rating scale. This can be compared to the ratings used for common vehicle gasoline 
ranging from 87-91 that you would see on gasoline pumps.

Isobutane is also an excellent refrigerant and is commonly used as such. In the 
past 30 years, it has been used as a replacement for other refrigerants known as 
chlorofluorocarbons seeing as they are responsible for major damage to the ozone layer.
These chlorofluorocarbons are known as R-12, R-22, and R-134a, commonly known by 
the name of Freon. Isobutane serves as a proper replacement to these because it has 
very low global warming potential and insignificant ozone depletion potential.
Other methods of application include its use as a propellant in aerosol products 
since it is naturally odorless, non-toxic, and non-corrosive. Also, its use in the 
manufacturing of polyurethane plastics. 

Although it is non-toxic and non-corrosive, it is important to remember that 
isobutane vapor is highly flammable and poses a dangerous fire hazard. Along with 
these, if the vapor is inhaled it can cause irritation to the nose, throat, eyes, and skin as 
well as suffocation if levels are high enough. Contact with isobutane in liquid form has a 
risk of causing frostbite, for this reason any contact with the liquid should be rinsed with 
large amounts of warm water for at least 15 minutes. Inhalation of the vapor should 
result in removal of the person from exposure and promptly being treated at a medical 
facility.

There are two distinct isomerization processes; butane, which was talked about 
above, and pentane/hexane. Pentane/hexane isomerization increases the octane 
number of the light gasoline components n-pentane and n-hexane, which are found in 
abundance in straight-run gasoline (Nicholas P. Cheremisinoff, 2009). In a typical 
pentane/hexane isomerization process, desulfurized and dried feed is mixed with 
recycled hydrogen and organic chloride, then heated to the temperature of the reactor. 
Benzene and Olefins are hydrogenated after passing the mixture over supported-metal 
catalyst in the first reactor and then flows into the isomerization reactor. In the 
isomerization reactor the paraffins are turned into isoparaffins by being catalytically isomerizes. The effluent of the reactor is then cooled and separated into two streams.
The two streams are a recycled hydrogen stream, and a liquid product called an 
isomerate. The isomerate is washed with caustic and water, acid stripped, and stabilized 
before going to storage (Nicholas P. Cheremisinoff, 2009).

Purpose 
Of the many purposes to this project, one of the more important is to prepare 
students to work as an effective team member. This can give insight into future work as 
a project manager in a professional environment. 
Another main purpose is to apply previously learned skills to model a chemical 
engineering process. By doing so, this assists in familiarizing students with real 
industrial practices. To accomplish this, various elements of courses that have been 
completed have been brought together to be used simultaneously. This project includes 
elements from, but not limited to, process control, thermodynamics, heat transfer, 
energy and mass balance, and differential equations. All of these have been applied to 
design a proper reactor for the isomerization of n-butane. Furthermore, this project 
assists in growing members' ability to perform data analysis and draw conclusions. 

Risk Assessment 
What If List:
• Temperature control malfunctions and causes butane to ignite
• Pressure leak leading to explosion
• Heat exchanger leak leading to contamination of butane
• Water corrosion of heat exchanger pipes
• Flow is not maintained leading to uncontrolled reaction potential
• No heat exchange leading to no reaction
• Loss of heat causing minimal reaction
• Human error leading to change in variables not designed for process
• Loss of control for mixer leading to minimal reaction
• Non-consistent heating leading to unpredicted change in concentration at end of 
reaction.
If a pressure leak were to occur, butane would come out of the reactor as a gas 
due to the initial temperature being 320K (47C) which is above the boiling point of 
butane, which is 31.2C. Since that is the lowest temperature in the process it could lead 
to a vapor fire if butane were to escape the process into the surrounding environment
(Inchem, 2022). If the correct materials for construction of the reactor are not used, it 
could lead to possible corrosion of the reactor which could then lead to a pressurized 
leak. With the wrong materials used the likelihood of this event happening is likely to 
happen. If an explosion were to happen because of the leak it would have consequences 
in the major category. Overall, with the consideration of both of those criteria in place, 
the event is placed under elevated risk.

If the heat exchanger were to leak into the process it would lead to contamination 
of the butane. This will cause the loss of desired product from the process and loss of 
control over the process which would lead to unwanted side reactions if not answered 
immediately upon the start of the incident. Overall, the likelihood of this event is 
unlikely since most heat exchangers are designed to hold water and not corrode with 
water present. If this event were to happen, it would yield minor consequences. This 
would mean that the level of risk level of this specific event is of moderate risk.
A loss of control over the mixer for the reactor would yield uneven mixing which 
in turn would mean an uneven reaction taking place. The mixer is used to make sure the 
butane is evenly combined so that the heat transfer is evenly distributed across the 
reactor. With this not in working operation, the amount of desired product cannot be 
predicted and could increase the yield of undesired product. This could lose money for 
the company since it would be less product being created. Seeing that this is not likely 
happen, it is put into the rare likelihood. The consequences for this event would also be 
minor as one reactor going down would not yield injuries and would just be a loss in 
productivity. This would make the risk under moderate risk.

To fix two of these issues, choosing the correct material for the job is essential. 
Stainless steel is normally the go to material that is not likely to react with both butane 
and water. Stainless steel is known for having properties that are resistant to rust
(Docslib, 2022). Since the environment will also not be introduced to oxygen, as that 
would lead to high potential of butane ignition, the pipes and reactor will last longer. 
While stainless steel might take longer to heat up as part of a heat exchanger, it will 
yield consistent results over time if water is reused in this process. By using stainless 
steel as a contact point, you can get even heating that will eliminate the variable of 
spotty heat transfer. Overall, the use of stainless steel, while expensive, has benefits that 
no other material has in comparison and as such should be used for this reacto

Data Collection 
Assumptions:
• Closed batch system with constant volume
• Steady State for the heat exchanger
• No reactions inside the heat exchanger 
• Constant specific heat capacities
• No heat from mixing
• No heat loss to surroundings
• Shaft work is negligible
• No Phase Changes
• Constant Heat Capacity of water and reactants
• Constant Density of water and reactants
• Perfect Mixing

Derivations of Differential Equations
Mass Balance for Reactor(Component A)

Conservation Equation
𝑀 ̇𝑖𝑛 − 𝑀̇𝑜𝑢𝑡 + 𝑀 ̇𝑛𝑒𝑡 𝑔𝑒𝑛 = 𝑀 ̇𝑎𝑐𝑐
Simplified (assume no in, no out, no accumulation) A batch reactor is a closed system, 
with a constant volume.
𝑀 ̇𝑛𝑒𝑡𝑔𝑒𝑛 = 𝑟𝑎(𝑡)
𝑑𝐶𝑎/𝑑𝑡 = 𝑟𝑎(𝑡)

Rate of reaction of a isobutane
𝑟𝑎(𝑡) = 𝑘𝑓(𝑡)(𝐶𝑎(𝑡) −𝐶𝑏(𝑡)/𝐾𝑒𝑞(𝑡))

Rate of reaction of n-butane
𝑟𝑏(𝑡) = −𝑟𝑎(𝑡)
𝑑𝐶𝑏/𝑑𝑡 = −𝑟𝑎(𝑡)

Reaction rate constants:
Forward reaction rate constant: t1=360, Trr(t) = temperature of reactor with 
respect time.
𝑘𝑓(𝑡) = 𝑘1𝑒^𝑒𝑎/𝑅(1/𝑇1−1/𝑇𝑟𝑟(𝑡))

Equilibrium reaction rate constant: T2=333
𝑘𝑒𝑞(𝑡) = 𝑘𝑒𝑞𝑇2𝑒^𝐻𝑟/𝑅(1/𝑇2-1/𝑇𝑟𝑟(𝑡))

Mass Balance for Heat Exchanger
Conservation equation
𝑀 𝑖𝑛 − 𝑀̇𝑜𝑢𝑡 + 𝑀 ̇𝑛𝑒𝑡 𝑔𝑒𝑛 = 𝑀 ̇𝑎𝑐

Simplified (assume steady state, no phase change, no reactions in the heat exchanger)
𝑀 ̇𝑖𝑛 = 𝑀̇𝑜𝑢𝑡
𝑀 ̇𝑖𝑛 = 𝑞𝑐ρℎ2

Energy Balance for Heat Exchanger
Conservation Equation
𝐸 ̇𝑖𝑛 − 𝐸 ̇𝑜𝑢𝑡 + 𝐸 ̇𝑛𝑒𝑡 𝑔𝑒𝑛 = 𝐸 ̇𝑎𝑐

Expanded energy conservation equation
𝑄 ̇𝑖𝑛 − 𝑄̇𝑜𝑢𝑡 + 𝑊̇𝑖𝑛 + 𝑊̇𝑜𝑢𝑡 + Σ𝑚̇𝑖𝑛 − Σ𝑚̇𝑜𝑢𝑡 ± 𝑟𝑉𝐻𝑟=d(ρℎ20V𝐻𝐸𝐶ℎ20T𝐻𝐸)/𝑑t
Simplified (assume no heat of mixing, no heat loss to surroundings, shaft work is 
negligible, no phase change, constant volume, constant density
𝑈𝐴ℎ𝑒(𝑇𝑅𝑅 − 𝑇𝐻𝐸) + 𝑞𝑐ρℎ20𝐶ℎ20(𝑇𝐻𝐸 − 𝑇𝑐𝑖) = ρℎ20V𝐻𝐸𝐶ℎ20 ∗ dT𝐻𝐸/𝑑t

Batch Reactor Energy Balance
Conservation Equation
𝐸 ̇𝑖𝑛 − 𝐸 ̇𝑜𝑢𝑡 + 𝐸 ̇𝑛𝑒𝑡 𝑔𝑒𝑛 = 𝐸 ̇𝑎𝑐

Expanded energy conservation equation
𝑄 ̇𝑖𝑛 − 𝑄̇𝑜𝑢𝑡 + 𝑊̇𝑖𝑛 + 𝑊̇𝑜𝑢𝑡 + Σ𝑚̇𝑖𝑛 − Σ𝑚̇𝑜𝑢𝑡 ± 𝑟𝑉𝐻𝑟=d(ρ𝑏𝑢𝑡𝑎𝑛𝑒V𝑅𝑒𝑎𝑐𝑡𝑜𝑟𝐶𝑏𝑢𝑡𝑎𝑛𝑒T𝑅𝑅)/𝑑t

Simplified (assume no heat of mixing, no heat loss to surroundings, no phase change, 
constant heat capacity, constant density, constant volume, perfect mixing)
−𝑈𝐴ℎ𝑒(𝑇𝑅𝑅 − 𝑇𝐻𝐸) − 𝑟𝑎V𝑅𝑒𝑎𝑐𝑡𝑜𝑟𝐻𝑟 = ρ𝑏𝑢𝑡𝑎𝑛𝑒V𝑅𝑒𝑎𝑐𝑡𝑜𝑟𝐶𝑏𝑢𝑡𝑎𝑛𝑒*𝑑T𝑅𝑅/𝑑𝑡

4 Differential Equations:
𝑑𝐶𝑎/𝑑𝑡 = 𝑟𝑎(𝑡)
𝑑𝐶𝑏/𝑑𝑡 = −𝑟𝑎(𝑡)
𝑈𝐴ℎ𝑒(𝑇𝑅𝑅 − 𝑇𝐻𝐸) + 𝑞𝑐ρℎ20𝐶ℎ20(𝑇𝐻𝐸 − 𝑇𝑐𝑖) = ρℎ20V𝐻𝐸𝐶ℎ20 ∗ dT𝐻𝐸/𝑑𝑡
−𝑈𝐴ℎ𝑒(𝑇𝑅𝑅 − 𝑇𝐻𝐸) − 𝑟𝑎V𝑅𝑒𝑎𝑐𝑡𝑜𝑟𝐻𝑟 = ρ𝑏𝑢𝑡𝑎𝑛𝑒V𝑅𝑒𝑎𝑐𝑡𝑜𝑟𝐶𝑏𝑢𝑡𝑎𝑛𝑒*𝑑T𝑅𝑅/𝑑t

DOF Analysis
(1) 𝑑𝐶𝑎/𝑑𝑡= 𝑟𝑎(𝑡)
(2) 𝑑𝐶𝑏/𝑑𝑡= −𝑟𝑎(𝑡)
(3) 𝑘𝑓(𝑡) = 𝑘1𝑒^𝑒𝑎/𝑅(1/𝑇1-1/𝑇𝑟𝑟(𝑡))
(4) 𝑘𝑒𝑞(𝑡) = 𝑘𝑒𝑞𝑇2𝑒^𝐻𝑟/𝑅(1/𝑇2−1/𝑇𝑟𝑟(𝑡))
(5) 𝑈𝐴ℎ𝑒(𝑇𝑅𝑅(𝑡) − 𝑇𝐻𝐸(𝑡)) + 𝑞𝑐ρℎ20𝐶ℎ20(𝑇𝑐𝑖 − 𝑇𝐻𝐸(𝑡)) = ρℎ20V𝐻𝐸𝐶ℎ20*𝑑T𝐻𝐸/𝑑𝑡
(6) −𝑈𝐴ℎ𝑒(𝑇𝑅𝑅(𝑡) − 𝑇𝐻𝐸(𝑡)) − 𝑟𝑎(𝑡)V𝑅𝑒𝑎𝑐𝑡𝑜𝑟𝐻𝑟 = ρ𝑏𝑢𝑡𝑎𝑛𝑒V𝑅𝑒𝑎𝑐𝑡𝑜𝑟𝐶𝑏𝑢𝑡𝑎𝑛𝑒*𝑑T𝑅𝑅/𝑑t

Parameter # Explanation
Constants 16 𝑈𝐴ℎ𝑒, 𝑞𝑐, ρℎ20, 𝐶ℎ20, V𝐻𝐸, V𝑅𝑒𝑎𝑐𝑡𝑜𝑟, 𝐻𝑟, 𝐶𝑏𝑢𝑡𝑎𝑛𝑒, 𝑇𝑐𝑖,ρ𝑏𝑢𝑡𝑎𝑛𝑒 𝑘1, 𝑘𝑒𝑞𝑇2, 𝑒𝑎, 𝑅, T1,T2,
Variables 7 𝑟𝑎(𝑡), T𝑅𝑅(𝑡), T𝐻𝐸(𝑡), 𝐶𝑎(𝑡), 𝐶𝑏(𝑡), 𝑘𝑓
(𝑡), 𝑘𝑒𝑞(𝑡)
Equations 6 Equations 1,2,3,4,5,6

DOF = Variables -
Equations 1
1 variable to be 
specified
t-time to be 
determined
Controlled Variable: T𝑅𝑅(𝑡)

Disturbance Variables: T𝐻𝐸(𝑡), 𝑘𝑓(𝑡), 𝑘𝑒𝑞(𝑡), 𝑟𝑎(𝑡),
Manipulated Variable: Ca

Overall heat transfer coefficient
𝑈𝐴ℎ𝑒 = (1/𝐻𝐻𝐸π 𝐷𝑜𝐿+log [𝐷𝑜/𝐷𝑖]/2πLKHE+1/𝐻𝑅𝑒𝑎𝑐𝑡𝑜𝑟π ∗ Di ∗ L)^−1
Where,
Heat transfer coeffecienct for Heat Exchanger 𝐻𝐻𝐸 = 300 (𝑊/𝑚2𝐾)
𝐻𝑒𝑎𝑡 𝑡𝑟𝑎𝑛𝑠𝑓𝑒𝑟 𝑐𝑜𝑒𝑓𝑓𝑒𝑐𝑖𝑒𝑛𝑡 𝑓𝑜𝑟 𝑅𝑒𝑎𝑐𝑡𝑜𝑟 𝐻𝑅𝑒𝑎𝑐𝑡𝑜𝑟 = 400(𝑊/𝑚2𝐾)
𝑇ℎ𝑒𝑟𝑚𝑎𝑙 𝐶𝑜𝑛𝑑𝑢𝑐𝑡𝑖𝑣𝑖𝑡𝑦 𝑜𝑓 𝑅𝑒𝑎𝑐𝑡𝑜𝑟 𝐾𝐻𝐸 = 50 (𝑊/𝑚𝐾)
𝑂𝑢𝑡𝑠𝑖𝑑𝑒 𝑑𝑖𝑎𝑚𝑒𝑡𝑒𝑟 𝑜𝑓 𝐻𝑒𝑎𝑡 𝐸𝑥𝑐ℎ𝑎𝑛𝑔𝑒𝑟 𝑃𝑖𝑝𝑒 𝐷𝑜 = 0.025(𝑚)
𝐼𝑛𝑠𝑖𝑑𝑒 𝐷𝑖𝑎𝑚𝑒𝑡𝑒𝑟 𝑜𝑓 𝐻𝑒𝑎𝑡 𝐸𝑥𝑐ℎ𝑎𝑛𝑔𝑒𝑟 𝑃𝑖𝑝𝑒 𝐷𝑖 = 0.02(𝑚)
𝐿𝑒𝑛𝑔𝑡ℎ 𝑜𝑓 𝐻𝑒𝑎𝑡 𝐸𝑥𝑐ℎ𝑎𝑛𝑔𝑒𝑟 𝐿 = 5(𝑚)
So,
𝑈𝐴ℎ𝑒 = 58.69 𝑤/

Figures
Figure 1. Batch Reactor Isomerization of Isobutane to N-butane Over Time

Figure 2. Temperature Response from Isomerization of Isobutane to N-butane Over Time

Figure 3. Conversion of n-butane

Figure 4. Batch Reactor Isomerization of Isobutane to N-butane Over Time with 
Proposed Change

Figure 5. Temperature Response from Isomerization of Isobutane to N-butane Over 
Time with Proposed Change

Figure 6. Conversion of N-butane with Proposed Change


Results and Discussion
In Figure 2, it can be observed that after 110 seconds the temperature of the 
reactor exceeds 400K. Stopping the reaction before the temperature of the reactor 
exceeds 400K would prevent a phase change from occurring (N-Butane final copy.nb). 
Alternatively lowering the initial concentration of isobutane would effectively limit the 
amount of energy capable of being produced by this reaction preventing the reactor 
temperature from exceeding 400k. Keeping the initial concentration of isobutane below 
24 mol/l would enable this(N-Butane final copy with proposed change.nb). 

Conclusion 
This commonly used item, isobutane is created through a process of 
Isomerization. Through this project the team has learned to work together and work 
with a team leader to create a successful demonstration of this reaction. With the results 
that have been determined from this project, the team recommends that we run this 
reaction not as a batch reactor, but as a semi batch reactor or a form of a CSTR with a 
transmitter reading the temperature of the vessel controlling a valve on the exit to 
remove product when the reaction reaches 390K. To come to this recommendation, it 
was based on our Mathematica file that provided the data above also while using some 
assumptions such as constant volume, no heat loss to surrounding, shaft work being 
negligible, and many others listed above. This reaction can be dangerous so here are 
some key elements to remember, n-Butane is a flammable chemical, so ignition sources 
need to be watched and kept away from the vessel as much as possible. The vessel is a 
highly pressurized vessel with that safety precautions must be taken when operating and 
more importantly designing the vessel. This reaction and chemical can cause a runaway
reaction potentially escalating to catastrophic failure if not observed carefully. With 
these recommendations isobutane can be successfully and safely created through 
isomerization.

Works Cited 
Docslib. (2022, October 14). 304 Stainless Steel Corrosion Compatibility Chart 304 Stainless Steel 
Corrosion Compatibility Chart. Retrieved from Docslib: https://docslib.org/doc/6314593/304-
stainless-steel-corrosion-compatibility-chart-304-stainless-steel-corrosion-compatibility-chart
Inchem. (2022, October 11). n-butane. Retrieved from Inchem: 
https://inchem.org/documents/icsc/icsc/eics0232.htm
LPG Gas Blog. (2022, 09 29). What is Isobutane? i-Butane - What is the Use of Isobutane? Retrieved from 
ELGAS: https://www.elgas.com.au/blog/2077-what-is-isobutane-i-butane-is-an-lpg-gasliquefied-petroleum-gas/
Nicholas P. Cheremisinoff, P. R. (2009). The Petrolium Industry. In Best Practices in The Petroleum 
Industry. Oxford: Linacre House.
Salvo, Z. (2022). Isomerization. Retrieved from SET Labratories Inc: 
http://www.setlab.com/resources/refining/isomerization/#1498503298829-9704cdcf-e64b
Sie Neftehim. (n.d.). Butane Isomerizatoin. Retrieved from SEI NEFTEHIM: 
https://nefthim.com/manual/butane-isomerization/

Appendix 
N-butane final copy.nb
N-butane final copy with proposed changes.n


