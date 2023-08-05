# What is triggering? 
Triggering helps to synchronise the incoming signal with the display of the scope. When the scope is not triggered (synchronised). 

A good way to see for your self what an unsynchronised scope looks like is to attach your probe to the square wave signal generator of your scope (usually at the bottom right hand corner), and rotate the trigger knob so its completely above or below the signal. You will immediately notice that the waveform displayed is no longer a smooth square wave as it starts jumping across your screen. If you don't have a scope on hand, this [video](https://www.youtube.com/watch?v=j2vch6wAddc) by Keysight provides a great visualisation of it.

![scope_square_wave_gen_image](./img/picture.png)

# Trigger modes
By default, your oscilloscope will be on 'auto' trigger mode and will continuously show you whatever is being fed into it. However, there are situations were you want to capture a particular moment with your signal and not the entire thing, such a spike above a certain voltage or the transition from 0 V to 5 V. This is where trigger modes come in. 

Different scopes offer different types of trigger modes, but common ones are triggering during a low to high transition or when a certain gradient is observed in the signal. As usual, your scopes manual will detail all the trigger modes available to you. This is the [manual](https://www.manualslib.com/manual/2678098/Siglent-Sds1022dl.html?page=49#manual) for the scope found in the NUS E2A Electronic Lab, on the section 'Trigger Types'.
