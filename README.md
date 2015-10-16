stm32f4-discovery-breakout-board
================================

The $15 STM32F4-Discovery ARM Cortex M4 development board is an amazing price but it unfortunately has columns of male pin headers that are awkwardly positioned so you can't use it directly with a standard breadboard.

This pair of breakout boards takes the male pins to female headers. If you don't mind a permanent solution, you can solder the boards directly to the male pins and save $5 in 2x25-pin female headers.

The git repo contains Eagle files and generated fab-ready gerbers for the STM32F4-DISCOVERY breakout board. The complete build log is on <a href="http://jennerhanni.net/2015/02/stm32f4-disc-breakout/">my site with more photos</a>.

You definitely want to use version 2 but I'm including version 1, even if you're routing this on a home PCB router. All traces are on the bottom side so there's no need for plated through holes if you're using the 2x25-pin female headers. Place the components on the top of the breakout boards and solder the pins on the bottom side. It'll come out just fine.

Total cost for your own set of three is $45.37.

I shared the project so you can <a href="https://oshpark.com/shared_projects/GJyFucOY">order boards for $33.95 from OSH Park</a>.

I used these Sullins female headers:  

- Qty 4 of <a href="https://www.digikey.com/product-detail/en/PPTC251LFBN-RC/S7023-ND/810163">PPTC251LFBN-RC</a> 1×25 0.1" for $1.41 each
- Qty 2 of <a href="https://www.digikey.com/product-detail/en/SFH11-PBPC-D25-ST-BK/S9201-ND/1990094">SFH11-PBPC-D25-ST-BK</a> 2×25 0.1" for $2.89 each.

The project is released under the <a href="http://www.ohwr.org/attachments/2388/cern_ohl_v_1_2.txt">CERN Open Hardware License v1.2</a>. 

<img src="https://jenner.smugmug.com/STM32-Discovery-Breakout/i-TV7kmhd/0/L/stm32-v2-side-L.png">
