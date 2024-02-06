# Gitplay_4

SYS1.CPWR.MLCX170.SLCXLOAD
ISPW.PLAY.DEV1.LOAD
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 git_token

ssh-rsa AAAAB3NzaC1yc2EAAAADAQABAAACAQCkxL3YDF4uHqw43ODexEJ6VIuJ3Utw/nZK/jqOwq1d0IFKugUTNrm2NvrUh9hR0l145Izi9DmHbWSpQj8GZBFAOyo102yuSN7K4PB8MCoRjkizsl06UHJ6T5/ENMqY4nQFZNKUJW/axhL2LvZYG2j6oWjpDSqvgvGQaWIfPcUpVRJjpNn5DwROpnXAIE7k3iTPlQYw1WB/Ez9nR82P7ak1q2Zeo3yoT9No8YRzd7I7EWrne5kx1B68JZcCdut9cYVoA4fg7c+1beMfxUVxHNuQMulsxCAu7LHnwWDWcD8pkD5hOBcMEQeqQnCjJQM7z3mJp6uidqx+oHienqQJFSGaR1oc7LJVkfdl85Bc1Ev5jVt9Gv1c36W5IQQyZWzYxWEZXftuJ1es5HHd6sdpTFLJKEG41IPjHYzLYQcDrvW3H6IkL3jEe6AR4z1531AV/9EpotYzIcjex1wrDNGL8BWbAc4RuUJTOoo0bhGsb0G1mJLy3UnDM2EPY28hOVCSAb+1n8Is8DjwWSI6bPy7K58p1C7C8a9U1tsFNmSqj3Wslh3j12Sw6p1bY7+5Tw+lHdv0Wdw4tobYx8hnLR83RY9LbyOZspQfV7wl/FJhHJEGIlbKGMa0HrAm46w88VOkQjqc86xiJRNdEgRHebOBuotPauzPxlTdaN3MZgu6gPSTtw== saikiran@popup-mainframe.com

 //JOBNAME JOB ('ACCOUNTING INFO'),'NAME',NOTIFY=&SYSUID,CLASS=A,
//        MSGCLASS=R,REGION=0M

- path: \COB
   types:
   - cics: 'No'
     fileExtension: cob
     flag1: A
     flag2: B
     flag3: C
     flag4: D
     genParms: GENPARMS
     ims: 'No'
     ispwType: COB
     progType: 'Yes'
     sql: 'No'
     
 - path: \COB
    types: 
    - fileExtension: cob
      ispwType: COB 
      progType: 'Yes'
      cics: 'No'
      sql: 'Yes'

on:
  push:
    paths:
      - 'COB/**'
