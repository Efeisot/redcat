# RedCat
![IMG_20240719_045730_387](https://github.com/user-attachments/assets/9d63bfa7-408c-4fd0-93e3-425ace7b0b23)

This repository explains why you should avoid Red Hat and the stuff they sponsor/develop, similar to the ManjarNo repository on GitHub.

## 1. Red Hat and Red Hat Enterprise Linux
### GPL Violation:
·	Red Hat, as you know, has recently caused GPL violations. The main source of the problem is that the RHEL terms of use allow Red Hat to revoke the license if the source code is modified. Normally, the GPL license allows for modifications to the source code and for it to be forked and redistributed. Red Hat seems to be spitting in its own soup by forcing users to stay within the standard options it provides.

https://www.jeffgeerling.com/blog/2023/im-done-red-hat-enterprise-linux

https://sfconservancy.org/blog/2023/jun/23/rhel-gpl-analysis/

### Lack of KDE support and GNOME imposition:
·	Red Hat does not include KDE in its RHEL repositories and instead forces GNOME as the default desktop on users, forcing those who want to use KDE to switch to Fedora. They also seem to lack the ability to distinguish between free and non-free packages, or they are afraid that an alternative desktop like KDE will overshadow GNOME.

https://www.reddit.com/r/kde/comments/bv9pl3/its_official_rhel_8_does_not_include_kde_at_all/

https://www.cyberciti.biz/linux-news/kde-deprecated-in-rhel-7-6-future-version/

### Promise to Microsoft to "not make Linux the first choice on personal systems" (I will add the link when I find it, it is a bit old and therefore difficult to find.)

## 2. Fedora
### Unnecessary prominence of GNOME on the main website and hiding of other options in the corners of the site:
·	You can see this for yourself by visiting Fedora's website and seeing how much the GNOME desktop editions overshadow the other spins. You have to do extra searches to download images of alternative editions like Spins and Fedora Everything, which can lead to uninformed users not being aware of these alternatives (that they have) and not getting the attention other editions deserve by using GNOME.

https://fedoraproject.org/

### Slowness of DNF:
·	Have you ever experienced the process of updating or downloading packages being very slow or getting errors even though your internet speed is good enough and you have a stable connection? This has probably been experienced by most dnf users, I'm telling you from experience, even with a stable internet connection with 24-36Mbps (equivalent to 3-4 megabytes per second) download speeds were reduced to ridiculous amounts like 1KB/sec when pulling metadata from the repos, which made it take me 2 hours to do updates and generally caused me to encounter errors. There are many people suffering from this situation, you can check out the links I've left below.

https://discussion.fedoraproject.org/t/why-is-dnf-so-slow/65916

https://www.reddit.com/r/Fedora/comments/17c4091/why_is_dnf_so_horribly_slow/

https://www.reddit.com/r/Fedora/comments/uvefe0/dnf_insanely_slow/

### Slow response and sluggishness of the Anaconda Installer:
·	I don't need to say much about this, if you've used Fedora you've witnessed how slow and sluggish the Anaconda installer is. Be honest: didn't it feel much slower than installers like Calamares, Ubiquity and even archinstall?

https://www.phoronix.com/news/Fedora-Web-Installer-F41-Delay

https://forums.fedoraforum.org/showthread.php?p=1822553

### Users as guinea pigs for RHEL:
·	Don't forget that RedHat is a for-profit company. Updates that are coming to RHEL first come to Fedora and then to CentOS, so considering that most of their users use Fedora Workstation, which has the default GNOME desktop version, it wouldn't be wrong to say that they are lab rats for RedHat.

https://www.reddit.com/r/Fedora/comments/18wqmzg/comment/kg7d7ww/utm_source=share&utm_medium=web3x&utm_name=web3xcss&utm_term=1&utm_content=share_button 

### Long boot time:
·	Fedora boots much slower than most distributions, including Ubuntu. To tell you my own experience: the minimal Sway system I built with Everything took 53 SECONDS to boot on my system with a Sandisk Ultra 3D Dram SSD, while this time is usually around 10-20 seconds on other distributions. Again, I'm leaving links below to users who have experienced problems with this:

https://discussion.fedoraproject.org/t/slow-boot-time-on-fedora-39-kde/112610

https://discussion.fedoraproject.org/t/slow-boot-up-after-fedora-38-install/81660

## 3. GNOME
### Extension problems:
·	The GNOME desktop environment does not include many essential features by default, so you need to add them with extensions (including dock, appmenu, applets in the system tray). Also, if you are on a distribution that is constantly updating and you use a lot of extensions, you have probably experienced problems with your extensions when you update GNOME. This is why some users use GNOME with distributions that update from behind like Debian.

https://www.reddit.com/r/gnome/comments/1bmeo3i/gnome_46_another_update_and_extensions_are_broke/

### Abundance of missing features on the desktop and slow merging of features:
·	In addition to the extension issue, GNOME is known for being ironically feature-poor for its own applications. There's not much I can say about this, if you think hard enough, you'll agree with me enough when you see the link I've left below.

https://www.omglinux.com/gnome-thumbnails-file-picker/ 

### Despite claiming to have simplified the interface for touch devices, an extra interface like Phosh is being developed:
·	One of the main claims of GNOME's interface is that they want to support touch interfaces as well, but instead of using GNOME, they use Phosh, which is an interface they have developed separately for Linux distributions (droidian, manjaro arm, etc.) developed for phones and tablets. You can check it out by following the link below.

https://en.wikipedia.org/wiki/Phosh 
https://medium.com/@alex285/why-gnome-on-phones-will-fail-if-succeed-94777faf2af8

### Don't theme our apps website ( https://stopthemingmy.app/ ):
·	This is a website that is a testament to how one-sided GNOME developers think. You can read for yourself that they think their applications are broken by community-made themes and that they don't want users to go beyond the default themes. No other desktop environment developer group has ever published such a shameless open letter except GNOME developers. It is the user's most basic right to theme the interface and change the theme if they think it is a problem or don't like it.

## 4. GTK and Libadwaita 
### Terrible application icon and mouse cursor themes:
·	I'm generally of the opinion that tastes and colors cannot be discussed, but even if we compare Adwaita and Breeze at the simplest level, the Adwaita theme looks very old and ugly to the eye. Even as someone who doesn't use Breeze, if I compare the two themes, Breeze definitely looks much more modern. Making everything big and kind of "colorful" doesn't help with normal interfaces you would use on your computer. I bravely can say KDE's QT designs surpasses GNOME's "libadwaita" crap.

