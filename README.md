[Vesta Control Panel RELOADED](http://vestacp.com/)
==================================================

**This is my version/fork of vesta with my current contributions for use until they get merged to the main branch**

[![Join the chat at https://gitter.im/vesta-cp/Lobby](https://badges.gitter.im/vesta-cp/Lobby.svg)](https://gitter.im/vesta-cp/Lobby?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

* Vesta is an open source hosting control panel.
* Vesta has a clean and focused interface without the clutter.
* Vesta has the latest of very innovative technologies.

How to install (2 step)
----------------------------
Connect to your server as root via SSH
```bash
ssh root@your.server
```

Download the installation script, and run it:
```bash
curl http://vestacp.com/pub/vst-install.sh | bash
```

How to install (3 step)
----------------------------
If the above example does not work, try this 3 step method:
Connect to your server as root via SSH
```bash
ssh root@your.server
```

Download the installation script:
```bash
curl -O http://vestacp.com/pub/vst-install.sh
```
Then run it:
```bash
bash vst-install.sh
```

Then 
```bash
cd $VESTA
git init
git remote add origin https://github.com/pcfreak30/vesta.git
git fetch
rm bin/ func/ install/ LICENSE  src/ upd/ web/ -rf
git checkout reloaded
```
License
----------------------------
Vesta is licensed under  [GPL v3 ](https://github.com/serghey-rodin/vesta/blob/master/LICENSE) license

