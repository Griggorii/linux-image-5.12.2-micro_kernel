# linux-image-5.12.2-micro_kernel | LZMA | ZRAM LZ4_COMPRESS | IP6 OFF config
lzma , linux , kernel , x64 , micro size , image , nouveau: nVidia Riva/TNT/GeForce/Quadro/Tesla , mount good , merge config , gcc-10 , + obs cam support + new fs support , tty F5 F7 F2 | gdm3 lock F1 emulation , inlock F2 and А5 F7 , wayland support , 3G 4G LTE usb modem supports, CONFIG_KERNEL_LZMA=y , '9p' 'adfs' 'affs' 'afs' 'aufs' 'autofs4' 'befs' 'bfs' 'btrfs' 'cachefiles' 'ceph' 'cifs' 'coda' 'configfs' 'cramfs' 'dlm' 'ecryptfs' 'efivarfs' 'efs' 'f2fs' 'fat' 'freevxfs' 'fscache' 'fuse' 'gfs2' 'hfs' 'hfsplus' 'hpfs' 'isofs' 'jffs2' 'jfs' 'lockd' 'logfs' 'minix' 'ncpfs' 'nfs' 'nfs_common' 'nfsd' 'nilfs2' 'nls' 'ntfs' 'ocfs2' 'omfs' 'overlayfs' 'pstore' 'qnx4' 'qnx6' 'quota' 'reiserfs' 'romfs' 'squashfs' 'sysv' 'ubifs' 'udf' 'ufs' 'xfs'

Donate support micro kernel clean carma corporations: https://yoomoney.ru/to/410014959813799

Support ufw good + Support firewallD not support 

Example /boot/initrd.img-5.12.2 copy to developer folder rename initrd.img-5.12.2.tar.gz view arhive structure

FS: '9p' 'adfs' 'affs' 'afs' 'aufs' 'autofs4' 'befs' 'bfs' 'btrfs' 'cachefiles' 'ceph' 'cifs' 'coda' 'configfs' 'cramfs' 'dlm' 'ecryptfs' 'efivarfs' 'efs' 'f2fs' 'fat' 'freevxfs' 'fscache' 'fuse' 'gfs2' 'hfs' 'hfsplus' 'hpfs' 'isofs' 'jffs2' 'jfs' 'lockd' 'logfs' 'minix' 'ncpfs' 'nfs' 'nfs_common' 'nfsd' 'nilfs2' 'nls' 'ntfs' 'ocfs2' 'omfs' 'overlayfs' 'pstore' 'qnx4' 'qnx6' 'quota' 'reiserfs' 'romfs' 'squashfs' 'sysv' 'ubifs' 'udf' 'ufs' 'xfs'

Гном контрол центр в некоторых настройках пока некоторые пункты очень медленно открываются и придется делать новый билд этого центра и параметров питания. Ядро очень хорошо ускоряет wayland , а я напоминаю что wayland это для меня не панацея , а индикатор здоровья тех же иксов и чем быстрее работает wayland тем быстрее работают иксы и любое всякое против обломается об сказанное мною по скольку есть три слона на которых все это едет в виде ядра , драиверов xorg | pipe | drm, wayland и если что то из этого плохо сконфигурировано то зачем оно все надо как говорится чемодан флешка назад на винду long term. Что бы еще больше ускорить иксы и wayland подготовлен nemo в качестве shell оболочки https://github.com/Griggorii/Setting_dconf_linux_OS20.04_V39.0_By_Griggorii_Wayland_adaptation дефолт nautilus обновлю позднее и им лучше не пользоваться по скольку его скрипт еще не обновлен и dconf менее производительный либо есть уже готовая система https://youtu.be/9B-nTJyEZX0 где достаточно без sudo кликнуть по скрипту сделав его исполняемым. Огромная просьба не плодить более дистрибутивы под разными именами или если плодите не берите ничего отсюда это условие я собираюсь создавать только качество и мои инвестиционные кошельки пусты по причине времени , а его прошло всего 5 лет , а не 10 и еще ничего из моего не опробировано и попадает под ит сговор и цензор т.е настраивайте сами конфиг не берите тут , а взяв его тут с целью распространения в своем кулибинном дистрибутиве вы не более чем паразит коих полно и в правительстве которое не пошло на встречу именно настоящей разработке даже в виде пропоганды распростронения что бы упростило сбор инвестиционных средств , а начало брать отсюда лакомые кусочки и взяв его тут вы не научитесь настраивать если вы типа создаете даже свои кулибинный дистрибутив который потухнет как очередной антегрос или реинкарнируется под уже другим названием , взяв же вы будете очередным инд крякером удачно подобрав то что плохо лежит и выставив свои более популизированные дистры и не менее инвестиционные кошельки для себя же данную конфигурацию вне распространении используйте можете даже пересобрать взяв из boot сам конфиг, общее предложение выкидываем все из интернета оставляем только убунту , манжаро , дебиан , магию , сент и пару фряшек учитывая что еще есть всякие андроиды и хромиумы , альпаины хватит с головой чем видеть миллион новых гаруда ляиникс и всяких мхподобных у которых просто все вытащили и приклеили бирку бмв.

linux-libc-dev_5.12.3-1_amd64.deb на по какому то пока мне не известному феномену прибавляет в графике и сбилден по трафарету ранее составленного ядра 5.9.3 раздаваемого с ним дистрибутива на моем канале https://youtu.be/9B-nTJyEZX0 т.е если вы собрались делать билд используйте не linux-libc-dev_5.12.2-4_amd64.deb , а linux-libc-dev_5.12.3-1_amd64.deb , а там посмотрим что это за связь  стандартный linux-libc-dev лучше не использовать.

5.12.2 CONFIG_MODULE_SIG_KEY="certs/signing_key.pem" vs 5.12.0 CONFIG_MODULE_SIG_KEY=""

Module example i3 Notebook

-Loaded Modules-
ccm		: Counter with CBC MAC
uas
rfcomm		: Bluetooth RFCOMM ver 1.11
bnep		: Bluetooth BNEP ver 1.3
zram		: Compressed RAM Block Device
lz4_compress		: LZ4 compressor
binfmt_misc
nls_iso8859_1
nls_cp437
vfat		: VFAT filesystem support
fat
snd_hda_codec_hdmi		: HDMI HD-audio codec
snd_hda_codec_realtek		: Realtek HD-audio codec
snd_hda_codec_generic		: Generic HD-audio codec parser
snd_hda_intel		: Intel HDA driver
snd_hda_codec		: HDA codec core
snd_hda_core		: HD-audio bus
snd_hwdep		: Hardware dependent layer
acer_wmi		: Acer Laptop WMI Extras Driver
snd_pcm		: Midlevel PCM code for ALSA.
sparse_keymap		: Generic support for sparse keymaps
btusb		: Generic Bluetooth USB driver ver 0.8
btrtl		: Bluetooth support for Realtek devices ver 0.1
btbcm		: Bluetooth support for Broadcom devices ver 0.1
btintel		: Bluetooth support for Intel devices ver 0.1
cmac		: CMAC keyed hash algorithm
snd_seq_midi		: Advanced Linux Sound Architecture sequencer MIDI synth.
snd_seq_midi_event		: MIDI byte &lt;-&gt; sequencer event coder
uvcvideo		: USB Video Class driver
videobuf2_vmalloc		: vmalloc memory handling routines for videobuf2
snd_rawmidi		: Midlevel RawMidi code for ALSA.
videobuf2_memops		: common memory handling routines for videobuf2
intel_rapl		: Driver for Intel RAPL (Running Average Power Limit)
x86_pkg_temp_thermal		: X86 PKG TEMP Thermal Driver
intel_powerclamp		: Package Level C-state Idle Injection for Intel CPUs
videobuf2_v4l2		: Driver helper framework for Video for Linux 2
videobuf2_core		: Driver helper framework for Video for Linux 2
coretemp		: Intel Core temperature monitor
v4l2_common		: misc helper functions for v4l2 device drivers
kvm_intel
bluetooth		: Bluetooth Core ver 2.21
kvm
irqbypass		: IRQ bypass manager utility module
snd_seq		: Advanced Linux Sound Architecture sequencer.
videodev		: Device registrar for Video4Linux drivers v2
iwldvm		: Intel(R) Wireless WiFi Link AGN driver for Linux
mac80211		: IEEE 802.11 subsystem
joydev		: Joystick device interfaces
ecdh_generic		: ECDH generic algorithm
snd_seq_device		: ALSA sequencer device management
snd_timer		: ALSA timer interface
serio_raw		: Raw serio driver
media		: Device node registration for media drivers
input_leds		: Input -&gt; LEDs Bridge
iwlwifi		: Intel(R) Wireless WiFi driver for Linux
snd		: Advanced Linux Sound Architecture driver for soundcards.
soundcore		: Core sound module
cfg80211		: wireless configuration support
mei_me		: Intel(R) Management Engine Interface
mei		: Intel(R) Management Engine Interface
mac_hid
sch_fq_codel
parport_pc		: PC-style parallel port driver
ppdev
lp
parport
efivarfs		: EFI Variable Filesystem
ip_tables		: IPv4 packet filter
x_tables		: {ip,ip6,arp,eb}_tables backend module
autofs4
btrfs
raid10		: RAID10 (striped mirror) personality for MD
raid456		: RAID4/5/6 (striping with parity) personality for MD
async_raid6_recov		: asynchronous RAID-6 recovery api
async_memcpy		: asynchronous memcpy api
async_pq		: asynchronous raid6 syndrome generation/validation
async_xor		: asynchronous xor/xor-zero-sum api
async_tx		: Asynchronous Bulk Memory Transactions API
xor
raid6_pq		: RAID6 Q-syndrome calculations
libcrc32c		: CRC32c (Castagnoli) calculations
raid1		: RAID1 (mirroring) personality for MD
raid0		: RAID0 (striping) personality for MD
hid_generic		: HID generic driver
multipath		: simple multi-path personality for MD
linear		: Linear device concatenation personality for MD
usbhid		: USB HID core driver
hid
nouveau		: nVidia Riva/TNT/GeForce/Quadro/Tesla
i915		: Intel Graphics
crct10dif_pclmul		: T10 DIF CRC calculation accelerated with PCLMULQDQ.
crc32_pclmul
ghash_clmulni_intel		: GHASH Message Digest Algorithm, acclerated by PCLMULQDQ-NI
cryptd		: Software async crypto daemon
mxm_wmi		: MXM WMI Driver
i2c_algo_bit		: I2C-Bus bit-banging algorithm
psmouse		: PS/2 mouse driver
ttm		: TTM memory manager subsystem (for DRM device)
ahci		: AHCI SATA low-level driver
libahci		: Common AHCI SATA low-level routines
drm_kms_helper		: DRM KMS helper
syscopyarea		: Generic copyarea (sys-to-sys)
lpc_ich		: LPC interface for Intel ICH
sysfillrect		: Generic fill rectangle (sys-to-sys)
sysimgblt		: 1-bit/8-bit to 1-32 bit color expansion (sys-to-sys)
tg3		: Broadcom Tigon3 ethernet driver
fb_sys_fops		: Generic file read (fb in system RAM)
sdhci_pci		: Secure Digital Host Controller Interface PCI driver
drm		: DRM shared core routines
ptp		: PTP clocks support
sdhci		: Secure Digital Host Controller Interface core driver
pps_core		: LinuxPPS support (RFC 2783) - ver. 5.3.6
video		: ACPI Video Driver
fjes		: FUJITSU Extended Socket Network Device Driver
wmi		: ACPI-WMI Mapping Driver

