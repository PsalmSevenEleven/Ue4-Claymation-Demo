This project is an experiment in modifying animations with Blueprint logic. 
I was originally going to simply create stop-motion-style animations manually and import them to UE4, but I ran into the issue of blendspaces. 
If the blendspace between two animations wasn't triggered at exactly the right time, the 'framerates' of the two animations would desync, breaking immersion.
To solve this problem, I developed a system to take existing animations and reliably convert them into claymation through game logic, where I had more control over the stuttering effect.
If you see any way to improve my code (more elegant implementation, better performance, etc) please let me know in the discussion or issues.
