# Different types of displays which we can use:- 
1) 2 digit 7 segment display or two, 1 digit 7 segment display </br>
2) OLED display</br>
3) LCD display</br>
4) LED matrix display </br>

# Types of Decade Counters:- 
1) IC 4017B</br>
2) IC 7490	</br>
3) IC 4026B </br>

# DATASHEETS COLLECTED SO FAR:- 
1) [IC 7490](https://www.ti.com/lit/ds/symlink/sn74ls90.pdf?ts=1719915087798&ref_url=https%253A%252F%252Fwww.google.com%252F) </br>
2) [IC 4017B](https://www.ti.com/lit/ds/symlink/cd4017b.pdf?ts=1719911856768&ref_url=https%253A%252F%252Fwww.ti.com%252Fproduct%252FCD4017B%253Fbm-verify%253DAAQAAAAJ_____05HPLdb1uD4AADixi6J8YUTYc_d_kdCFv8G66Xj_7DmsV6gNNNGcfVzt8CoS4wM51qKKfH1sx4Ya4v0qWDmP_3wnoKivbwSDZgIbQWO_oHQ5q1-AmTYgJxX66ArvjON3fFpvgrH1wCr4W1RvtqB3Ht4yLXqGErtGkxe_Ydk5MnSaQYdM2AP3w-qI8qePW0s58Wub-qTreAYVzZsSzFDBZ_7yoTrnZFdnrDkfBH31heiiisFyg7OD2f_WG0cUzTDCQ3TPUBNiKnO4zZx9dYGWxPUrXxY0lJdaJsq6Qwn76ixu73yiNNOSoXs) </br>
3) [IC 4026B](https://www.ti.com/lit/ds/symlink/cd4026b.pdf?ts=1719915268042&ref_url=https%253A%252F%252Fwww.ti.com%252Fproduct%252FCD4026B%253Fbm-verify%253DAAQAAAAJ_____5olkFrqbnE2kH0j-YdOLOiRfQmZgVna-q9JOLN0WBXT9NgggaFQL1xW2-lar1Ujrr-ehLgbXT8QCmtujESaBw558G9RNwZgH_7YxwzQI9MQI03kJD2PXva2guZpVrTpuE5i98IrmZIi5tI8a4m0eXmV5_GP-5K5SbKiwfL9BaRPqsCU0UG5WfxEpw6fpFSPpHToUAckYvNfc-NNpHrZYPjgPFjtA6Ie20jSMDj5woC_8om6zQoaylQZ-O2T0PzVSOIVhUQvf5B7E4q0OdhcVivspup_pIJqSN8fX_I_T4PZ8fcWnN259Vp_) </br>
4) [2 digit 7-segment display](https://www.farnell.com/datasheets/95204.pdf) </br>
5) [1 digit 7-segment display](https://docs.rs-online.com/b51e/0900766b801bf827.pdf) </br>
6) [OLED display](https://www.vishay.com/docs/37902/oled128o064dbpp3n00000.pdf) </br>
7) [SSD1306](https://www.electronicscomp.com/datasheet/ssd1306-datasheet.pdf)
</br>

# Problems:- 
1) Matrix display is costly, so we are not using that. Also, it needs a lot of space.</br>
2) OLED diplays are often Arduino-compatible but, are they compatible with the simple counter ICs which we will be using?</br>
3) Small LCD displays are not available easily. LCDs which are used in digital watches, how do they make those LCDs?</br>
4) 7 segment is very cheap but its big in size.</br>
5) For the ICs, I will be needing IC pin holder which will take up more space.</br>

# Questions so far:- 
1) How many button switches are required? Should we override any switch? What is key-debouncing and how should we take care of it when it happens? </br>
2) If I use, two 7 segment displays, I will need to add a control signal to increment the digit at tens place only when digit at ones' place is changing from 9 to 0. So if second digit is zero, increment the first digit. How do you do this? Do we need logic gates for this? If yes, which all?</br>
3) If I use a two digit 7 segment display, will the counter be enough to display all the numbers from 0 to 99 or do i need an additional circuit to dipslay two digits.</br>
4) Should a button battery be used? </br>
5) Should the counter be on at all times? No. So, there needs to an on/off switch.</br>
6) How do you reset the counter? Should we use override? </br>
7) Will OLED display work with the ICs which I use? </br>