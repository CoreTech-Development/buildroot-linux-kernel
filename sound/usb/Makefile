#
# Makefile for ALSA
#

snd-usb-audio-objs := usbaudio.o usbmixer.o
snd-usb-lib-objs := usbmidi.o
snd-ua101-objs := ua101.o

# Toplevel Module Dependency
obj-$(CONFIG_SND_USB_AUDIO) += snd-usb-audio.o snd-usb-lib.o
obj-$(CONFIG_SND_USB_UA101) += snd-ua101.o snd-usb-lib.o
obj-$(CONFIG_SND_USB_USX2Y) += snd-usb-lib.o
obj-$(CONFIG_SND_USB_US122L) += snd-usb-lib.o

obj-$(CONFIG_SND) += usx2y/ caiaq/
