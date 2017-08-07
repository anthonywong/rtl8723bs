# Realtek 8723bs Linux WIFI driver

Since Linux 4.12, rtl8723bs has been merged. Therefore, this repo is now **obsolete**. 

~~~~
commit 554c0a3abf216c991c5ebddcdb2c08689ecd290b
Author: Hans de Goede <hdegoede@redhat.com>
Date:   Wed Mar 29 19:47:51 2017 +0200

    staging: Add rtl8723bs sdio wifi driver
    
    The rtl8723bs is found on quite a few systems used by Linux users,
    such as on Atom systems (Intel Computestick and various other
    Atom based devices) and on many (budget) ARM boards such as
    the CHIP.
    
    The plan moving forward with this is for the new clean,
    written from scratch, rtl8xxxu driver to eventually gain
    support for sdio devices. But there is no clear timeline
    for that, so lets add this driver included in staging for now.
    
    Cc: Bastien Nocera <hadess@hadess.net>
    Cc: Larry Finger <Larry.Finger@lwfinger.net>
    Cc: Jes Sorensen <jes.sorensen@gmail.com>
    Signed-off-by: Hans de Goede <hdegoede@redhat.com>
    Signed-off-by: Greg Kroah-Hartman <gregkh@linuxfoundation.org>
~~~~

Thanks for all the hard work of all kernel developers!
