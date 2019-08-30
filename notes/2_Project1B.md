## PeC - Health

## Review
### Project B - explore the use of Algorithms and Techniques of Supervision to Evaluate the Obstruction in Infusion Bombs
- there are two main techniques for infusion, some thing like
	* high: hydrated the patient when given him the medicine (European school)
	* low: concentrated medicine (American school)

- the obstruction problem, maybe the biggest problem
	* can be caused by the patient (when moving)
	* the nurse can forget to simply open the valve

- the bombs use a pressure sensors to detect possible obstruction
	* note that the sensors __do not__ touch the liquid
	* it is very common to give a false positive (something like 90% false positive)
	* how can that be on the marked? the market make the rules, and they cannot do it any better '-'

- it is important to note that most the liquids that are infused into the patient is saline
	* i.e. a single discharge on the sensors could kill the patient (so don't let it touch the liquid)

#### Project 1B (2 students) - MINE
- apply techniques of smart systems to detect anomalies on the infusions

## Next to do
- read the article of Felipe on ERAD of 2019/18

- look for the paper of the ... thesis

- download the DataSets
	* apparently it's all a bunch of txt files
		+ lots of cat, grep, pipe, cut and etc

## Re-review
- the sensors __cannot touch__ the medicine
	* any liquid for that matter
	* cross contamination
	* also the liquid solution is saline, which could lead to a electric discharge in the patient
		+ the smallest discharge could kill the patient

- so the sensors do not enter in contact with the liquid
	* that difficulty the precision to measure the right delivery of medicine

- this measure uses mechanical force over the equipment used

- the of bombs to lead the medicine to the patient
	* a occlusion (caused by N factors like patient movement, ...)

- the accumulation of pressure in the equipment can lead to __high__ dosage deliver in a small space of time

- so we need to __improve the oclusion detection__
	* there is a dataset with the profile of medicine delivery using those bombs

- we have the data about the behavior of the pressure in the delivery system
	* high peaks show high pressure in the delivery time

- do note that the equipment is slightly different in each one
	* e.g. different material resistance
