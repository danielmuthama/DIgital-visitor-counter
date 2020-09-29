   ## Designing a Bidirectional Digital Visitor Counter
   
[![Watch the video](https://raw.githubusercontent.com/danielmuthama/Go2/master/visitor.png/visitor2.png?token=AJVSXQWMT6OILTGBXFCWXQ27OOKK6)](https://youtu.be/XSitIIMb_y8)
[![Watch the video](https://raw.githubusercontent.com/danielmuthama/Go2/master/visitor.png/visitor2.png?token=AJVSXQWMT6OILTGBXFCWXQ27OOKK6g)](https://youtu.be/EE8rnNKstbc)

> Abstract
 This project presents a digital bidirectional visitor counter. The visitor counter is a reliable circuit that takes over the task of counting number of visitors in the room very accurately and beeps a warning alarm when the number of visitors exceeds the capacity limit of the hall. When somebody enters the room then the counter is incremented by one +1 and when any one leaves the room then the counter is decremented by one -1. The total number of persons inside the room is also displayed on the LCD. The microcontroller is used for detecting any entry or exit action and computing the figures (addition and subtraction) to acquire accurate results. It receives the signals from the sensors, and this signal is operated under the control of embedded programming code which is stored in ROM of the microcontroller. The microcontroller continuously monitors the Infrared Receivers. When any object passes through the IR Receiver's then the IR Rays falling on the receivers are obstructed. The obstruction occurs under two circumstances, either you obstruct sensor 1 (i.e. outside the building) before sensor 2 (i.e. which is inside the building) this shows that you are entering the building or you do it the other way round, which is obstructing sensor 2 before sensor 1 to indicates an exit movement. 
This obstruction is sensed by the Microcontroller, computed and displayed by a 16x2 LCD screen. Keywords: Digital bidirectional visitor counter, Receivers, Microcontroller, Liquid Crystal Display and Circuit.

> Introduction
  Visitor counting is simply a measurement of the visitor traffic entering and exiting conference rooms, malls, sports venues, etc. With the increase in standard of living, there is a sense of urgency for developing circuits that would ease the complexity of life. One of the most common things tally counters are used for is counting people, animals, or things that are quickly entering and existing a location. As times went on, an electronic tally counter was introduced which used an LCD screen to display the count, and a push button to advance the count. Some also have a button to decrement the count in case of a miscount. Now, due to technology advancement, various type of people counter has been introduced to automatically count the number of people entering and exiting a building at a particular time. Some of these are laser beam, thermal imaging, video camera and the infra-red sensor. All these sensors play their role respectively as visitor detector. These devices are very reliable and accurate in terms of performance as compared to the mechanical tally counter. 
In the past years, several well-established institutions across the globe have encountered various incidents related to traffic monitoring. It has been a necessity to monitor the visitors to carry out the human traffic management task and tourist flow estimate to vindicate accurate result for the organizational marketing and statistical research. This eventually indicates the patronage rate of goods and services by consumers. 
	Therefore, we deem it appropriate to identify these problems encountered by our various organizations and find solutions to them by designing a digital bidirectional visitor counter. The primary method for counting the visitors involves hiring human auditors to stand and manually tally the number of visitors who enter or pass by a certain location. The human auditing application or the human-based data collection was unreliable and came at great cost. For instance, in situations where a large number of visitors entering and exiting buildings such as conference rooms, law courts, libraries, malls and sports venues, going for human auditors to manually tally the number of visitors may result in inaccurate data collection. For this reason, many organizations have tried to find solutions to mitigate the inaccurate traffic monitoring issues. It is our intention to design and construct this digital bidirectional visitor counter with maximum efficiency and make it very feasible for anyone who wants to design and construct the prototype. Building this circuit will provide information to management on the volume and flow of people in a building. Our main objective in this paper includes designing and constructing a visitor counter which will make a controller-based model to count and compute the number of visitors in a building at a particular time. It is also our objective that this controller base model beeps a warning alarm when the capacity of the building is exceeded. 
	The significance of the design and construction in this paper is enshrined in the fact that it provides the assurance of the health and safety of the occupants in a building at all time, since the visitors are guaranteed of traffic decongestion. It also provides accurate data for various research and analytical purposes as it generates the hourly, daily, monthly, and yearly report. The device helps to reduces pressure on building facilities by prompting the security, when the capacity of the building is exceeded.
	 It goes a long way to assist rescue team or security services to come up with strategic procedure in dealing with emergency issues like people trapped in a structure as a result of hijacks and collapsed building which occurred recently at the West Gate Mall in Kenya. It is the usual norm that the design and construction of every device comes with some limitations and ours cannot be an exception. In this paper, our device might count more than two people as one when they interrupt the infrared beam at the same time in a linear direction. For this reason, the device must be installed at a narrow entrance/exit where one person enters at a time. Another limitation can be linked to the inability of sensor in the device to differentiate between human being and objects interrupting the IR signal. Finally, the device will fail to function in case of any power interruption, which might lead to a miscount or provide inaccurate data when power is restored. 
> Methodology
	This section introduces the methodology involved in the design and construction of the Digital Bidirectional Visitor Counter. Using the Takoradi Polytechnic Library crowd management situation as a case study, it was realized that the library’s capacity often gets exceeded during its peak usage period (examination period) and therefore makes the environment uncomfortable for learning. This problem was studied by visually observing student’s reaction anytime the library’s capacity was exceeded. The microcontroller-based visitor counter is designed to respond to the flaws in the operations of the existing counters. The design in its sense has four main sections and circuits. These include detection section (IR sensor circuitry), microcontroller section, alerting section (LCD and Buzzer) and power supply circuit. 

