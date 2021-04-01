### Hi Audiophile 👋

# MinDLNA to dimas-dastereo  setup instructions


###### Step by Step

#1./ **Download to Computer**
> https://raw.githubusercontent.com/lovehifi/minidlna-dastereo/main/minidlna-1.3.0-1-armv7h.pkg.tar.xz
> 
> https://raw.githubusercontent.com/lovehifi/minidlna-dastereo/main/glibc-2.32-2-armv7h.pkg.tar.xz
> 
> https://raw.githubusercontent.com/lovehifi/minidlna-dastereo/main/libexif-0.6.22-1-armv7h.pkg.tar.xz
>
####
####
#2./ **WinSCP Copy 3 file from PC to Pi /root/**
> minidlna-1.3.0-1-armv7h.pkg.tar.xz
>
> glibc-2.32-2-armv7h.pkg.tar.xz
>
> libexif-0.6.22-1-armv7h.pkg.tar.xz
####
####
#2./ **Extract**
> tar -xf /root/minidlna-1.3.0-1-armv7h.pkg.tar.xz --overwrite -C /
> 
> tar -xf /rootglibc-2.32-2-armv7h.pkg.tar.xz --overwrite -C /
>
> tar -xf /root/libexif-0.6.22-1-armv7h.pkg.tar.xz --overwrite -C /
>

####
#3./ **Config**

WinSCP edit file
>  /etc/minidlna.conf
Change folder music...
> 

####

####
#4./ **Start Service**

> systemctl daemon-reload
> 
> systemctl enable minidlna.service
> 
> systemctl restart minidlna.service
> 
> systemctl status minidlna.service
####
####
