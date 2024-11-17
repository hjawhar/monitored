# Monitored
### Docker & PM2 instances checker
<p>
Using russh client, the app would connect to the server and collect data of running docker and pm2 instances<br>
The following was initially designed to check my bots and other running services on my servers.<br>
I know that there are other tools out there that do the job, for my case, the goal was to connect to multiple servers at the same time, rather than  one-by-one and having to open a bunch of terminals and repeat the same process over and over again.
</p>

## Usage
```
$ cargo run host username port pk_path
```

![Screenshot](https://github.com/hjawhar/monitored/blob/master/screenshots/screenshot_1.png) 
