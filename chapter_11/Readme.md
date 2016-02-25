## Chapter 11

>Exercises in the chapter:

`$ mv awesome.txt uncool.txt`

`$ ls`
`newplace  uncool.txt`

`$ mv newplace oldplace`
`$ ls`
`oldplace   uncool.txt`

`$ mv oldplace newplace`
`$ ls`
`newplace   uncool.txt`

>Do more

`$ mv uncool.txt newplace`
`$ ls`
`newplace`

`ls newplace/`
`uncool.txt`

`$ mv newplace/uncool.txt uncool.txt`
`$ ls`
`newplace   uncool.txt`

Alternative "english" ways of asking for your working directory:

Can you rename foo.txt to blah.txt?

`$ mv foo.txt blah.txt`
`$ ls`
`blah.txt   newplace   uncool.txt`

Can you move the production.log file in the log directory to slash temp?

In my home directory I can change into `Library` and there is a `Log` directory.  I did not have a production.log file in there but the directions say that I may need to create it.
    `$ mkdir log`
    `$ touch log/production.log`
    `$ mv log/production.log /tmp`

    `$ cd /tmp`
    `$ ls`
    10454BD3-59AF-4676-8E5C-4A8B284B530D
    4AA91D2A-1178-4802-B818-6F06BAA5058F
    5480E28E-FB26-4C0F-A3D0-BD91D11BB028
    9EB32AC9-9303-496D-B082-C73EF6518BBC_IN
    9EB32AC9-9303-496D-B082-C73EF6518BBC_OUT
    AlTest1.err
    AlTest1.out
    C6820147-A500-443C-BE10-B79A2140CDD3
    EF0646CC-6820-45A6-BFB3-F09F7458D4C8
    ExmanProcessMutex
    F7C71944B49B446081C0603DE90E4855_IN
    F7C71944B49B446081C0603DE90E4855_OUT
    KSOutOfProcessFetcher.501.sAglCyxY5lzPoNgfmEvv-ZqGl-w=
    adobegc.log
    boost_interprocess
    com.adobe.AdobeIPCBroker.ctrl-laurielinz
    com.adobe.acrobat.rna.RdrCefBrowserLock
    com.adobe.reader.rna.0.1f5
    com.adobe.reader.rna.11d.1f5
    com.apple.launchd.C6soHy0ajO
    com.apple.launchd.DzlJ4e7qGs
    ct.shutdown
    foo.txt
    production.log
    swtag.log
    wifi-LVXxxY.log
    wifi-ON9GLy.log
    wifi-P2Vuff.log
    wifi-PwSVRL.log
    wifi-Rn7YDL.log
    wifi-Z7mMKc.log
    wifi-aEOp5d.log
    wifi-hKpNlm.log
    wifi-o8c6TM.log
    wifi-rLZQcg.log
    wifi-uYnW6r.log
    wifi-w6r2dC.log
