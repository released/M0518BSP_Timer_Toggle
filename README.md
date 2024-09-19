# M0518BSP_Timer_Toggle
 M0518BSP_Timer_Toggle

update @ 2024/09/19

1. init TIMER2 toggle : PB.10/TM2

    SYS->GPB_MFP &= ~(SYS_GPB_MFP_PB10_Msk);
	
    SYS->GPB_MFP |= (SYS_GPB_MFP_PB10_TM2);

2. below is PB.10 waveform capture

![image](https://github.com/released/M0518BSP_Timer_Toggle/blob/main/scope_1.jpg)


![image](https://github.com/released/M0518BSP_Timer_Toggle/blob/main/scope_2.jpg)

