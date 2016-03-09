>Alternative "english" ways of asking you to copy a file:

>Can you copy the foo.txt file to slash temp?  (Create foo.txt first...)

```
(master) Laurie Linz
Lauries-MacBook-Pro:chapter_10 $ cp foo.txt /tmp

(master) Laurie Linz
Lauries-MacBook-Pro:chapter_10 $ cd


Lauries-MacBook-Pro:~ $ cd /tmp


Lauries-MacBook-Pro:tmp $ ls
4E249C03-CD4D-498F-852F-7833A651D724
59229B12-3929-4DF7-9EC4-881FF491E454
59CD3513-83A4-4786-8857-9BC4ACAFDE0F
7E228831-DE60-4176-A34C-2A6447F75A5D_IN
7E228831-DE60-4176-A34C-2A6447F75A5D_OUT
84913E6F-E63C-433F-8027-03D5F717D308
8E49DEA1-84A8-4DC0-8B3D-E6B0846534D6
AlTest1.err
AlTest1.out
C92BBBB0-730D-4209-A6C3-AF051F9027A2.aamdownload
E15DB88C-EECF-420F-A2B6-C07BC04E85A3.aamdownload
ExmanProcessMutex
F7C71944B49B446081C0603DE90E4855_IN
F7C71944B49B446081C0603DE90E4855_OUT
KSOutOfProcessFetcher.501.ppfIhqX0vjaTSb8AJYobDV7Cu68=
adobegc.log
boost_interprocess
com.adobe.AdobeIPCBroker.ctrl-laurielinz
com.adobe.acrobat.rna.RdrCefBrowserLock
com.adobe.reader.rna.0.1f5
com.adobe.reader.rna.12f.1f5
com.apple.launchd.Cxpu4ItEcM
com.apple.launchd.Ra8T8eriF0
ct.shutdown
foo.txt
lilo.303
swtag.log
wifi-2CXWaD.log
wifi-2ys2Nq.log
wifi-49FQva.log
wifi-5lChSy.log
wifi-5sle7S.log
wifi-67xxXx.log
wifi-6jT3CE.log
wifi-8AVwOT.log
wifi-8NW1Dg.log
wifi-93Jbm3.log
wifi-CXA2IU.log
wifi-CZESSr.log
wifi-EsHTVA.log
wifi-FVjp5W.log
wifi-Fwtqjm.log
wifi-GkbSxP.log
wifi-GnHvB0.log
wifi-Gp3ESq.log
wifi-HR79pg.log
wifi-I5pUsS.log
wifi-IexFzv.log
wifi-JPfs37.log
wifi-JVstAN.log
wifi-KmoDl6.log
wifi-MWLyJr.log
wifi-MWs1HL.log
wifi-Mgq77z.log
wifi-NGNguE.log
wifi-RQ9et1.log
wifi-RwFfNu.log
wifi-SAgqM5.log
wifi-SKHTZt.log
wifi-T14l0X.log
wifi-TmHTRD.log
wifi-U6Rnll.log
wifi-UbbNqX.log
wifi-Udv4S8.log
wifi-VNGtbm.log
wifi-VUAQw5.log
wifi-Yv0S7J.log
wifi-Z9ojfN.log
wifi-ZHvVyz.log
wifi-ZdxETI.log
wifi-ZsoyM9.log
wifi-ZvWdSo.log
wifi-aK17wY.log
wifi-aWaBNx.log
wifi-aknDJc.log
wifi-apRpf9.log
wifi-awwKw0.log
wifi-bD8iPh.log
wifi-byWrSO.log
wifi-f9XjR2.log
wifi-gB9ATR.log
wifi-gOFvRJ.log
wifi-h1xYyH.log
wifi-hJlKrF.log
wifi-j4HC78.log
wifi-jR3u1p.log
wifi-jywXqC.log
wifi-kM0J0U.log
wifi-kXJ6HA.log
wifi-lcBaAm.log
wifi-mEaje4.log
wifi-msjfVK.log
wifi-mwoqK4.log
wifi-n674wH.log
wifi-nHCFYR.log
wifi-ntf5Jx.log
wifi-o620IX.log
wifi-oGNVhX.log
wifi-p1IizI.log
wifi-p2cL8s.log
wifi-p5dmLW.log
wifi-q51dlw.log
wifi-qjspU8.log
wifi-rR9YkU.log
wifi-rdVJnl.log
wifi-svYhsB.log
wifi-tK6c94.log
wifi-tXh06P.log
wifi-wow7uB.log
wifi-xmH45Y.log
wifi-xovvkX.log
wifi-xtyXmh.log
```

 
>Can you copy .bash_profile in your home directory to the current directory?

```
`$ cd ~`
`$ ls -a`
`$ cp .bash_profile ~/workspace/davinci_coders_t1_2016/homework/learn_command_line_exercises/chapter_10`
`$ cd ~/workspace/davinci_coders_t1_2016/homework/learn_command_line_exercises/chapter_10`

`$ ls -a`

.             .bash_profile Readme.md     tmp
..            .idea         foo.txt
```


Robocopy does not seem to have much to do with anything it is simply not a very intuitive function.  It means "Robust file copy" and it was used on older versions of windows. 

The command `cp -r` copies directories with files in them and since there was files in these directories you should be able to see my copies.  If you attemp to make a command involving a directory and you use the /, if the directory is not there, this will trigger and error. 
