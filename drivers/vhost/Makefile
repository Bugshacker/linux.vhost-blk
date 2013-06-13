obj-$(CONFIG_VHOST_NET) += vhost_net.o
vhost_net-y := net.o

obj-$(CONFIG_VHOST_SCSI) += vhost_scsi.o
vhost_scsi-y := scsi.o

obj-$(CONFIG_VHOST_VSOCK) += vhost_vsock.o
vhost_vsock-y := vsock.o
CFLAGS_vsock.o := -DDEBUG

obj-$(CONFIG_VHOST_RING) += vringh.o

obj-$(CONFIG_VHOST)	+= vhost.o
