# just-a-jmeter-thingy
The links and the notes that I listed when surfing jmeter.

# Jmeter 

So, I started my Jmeter journey watching automation step by step. I think its preety good. I'll attach all the video and the site link here. Thank you!! :D

    *https://www.javatpoint.com/jmeter-listeners
    *https://automationstepbystep.com/
    *Playlist I preferred: https://www.youtube.com/watch?v=SoW2pBak1_Q&list=PLtBmOtWUxgn2y075DQ3O52NLkprrHhjog&index=15&t=3s

Okay!! Lets roll out

# What is Jmeter?

Performance testing application
Built using Java
Recording
CLI
Multiple plugins

# Setting Up Jmeter
    Make sure java is installed in your system
    Download jmeter: https://jmeter.apache.org/download_jmeter.cgi    
    As I was using linux https://linuxhint.com/install_apache_jmeter_ubuntu/ this helped me but the article was kinda outdated
    
# Okay Now lets move on to how to create Jmeter test. I'll write whatever I found easy for me :)

1. Start Jmeter
2. Create a test plan
3. Create a thread group (Users)
    This means you need to add number of virtual users for the load test or performance test. They'll execute the same scenario. 
    Here's the link which I think was the good one
        https://www.redline13.com/blog/2018/05/guide-jmeter-thread-groups/
4. Add a sampler (HTTP)
    There are numbers of samplers available. By right clicking the thread groups you can add the samplers.
        https://www.toolsqa.com/jmeter/samplers/
    I'm using Zero Web App security that I used while learning cypress
        http://zero.webappsecurity.com/
5. Add Listeners
    To view the result/report we use listeners 
6. Run the test
