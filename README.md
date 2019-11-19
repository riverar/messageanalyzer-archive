# Microsoft Message Analyzer EOL Archive

![Message Analyzer splash screen](misc/splash.gif)

## License

 © 2014 Microsoft Corporation. All rights reserved.



## Notices

> Microsoft Message Analyzer (MMA) will be retired and its download packages removed from microsoft.com sites on **November 25 2019**.  There is currently no Microsoft replacement for Microsoft Message Analyzer in development at this time.  For similar functionality, please consider using a 3rd party network protocol analyzer tool such as WireShark.
>
> If you already have Microsoft Message Analyzer installed, you may continue to use it, along with the OPN parsers you have already downloaded. If you do want to continue using MMA, please make sure you have the latest versions of MMA and OPN parsers installed [...] 

— Microsoft Message Analyzer Blog, 11/11/2019 (https://docs.microsoft.com/en-us/openspecs/blog/ms-winintbloglp/dd98b93c-0a75-4eb0-b92e-e760c502394f)

> After November 25 2019 when MMA is launched, it will attempt to connect to the back-end Feed service to check News and Assets updates and an error message will appear. To dismiss this error message, see [the steps below].

— Microsoft Message Analyzer Operating Guide, 10/25/2016 (https://docs.microsoft.com/en-us/message-analyzer/microsoft-message-analyzer-operating-guide)



## Layout

`/releases` contains all archived releases of Message Analyzer. (At this time, it only contains the latest 1.4 release.)

`/feed` contains Open Protocol Notation (OPN) parser packages, UI feature configuration, and other assets once delivered via the Message Analyzer Asset Feed (https://maodatafeedsservice.cloudapp.net/MAODataAssets.svc/). An offline installation helper script is provided.

`/misc` contains miscellanea to support the repository.



## Steps to reconfigure Message Analyzer to work offline

1. Launch Microsoft Message Analyzer.
2. In the **Tools** menu, select **Asset Manager**.
3. In the **Asset Manager** window, click on the **Online** button to switch to **Offline** state.
4. Close and restart Microsoft Message Analyzer.