obj-$(CONFIG_VSOCKETS) += vsock.o
obj-$(CONFIG_VMWARE_VMCI_VSOCKETS) += vmw_vsock_vmci_transport.o
obj-$(CONFIG_VIRTIO_VSOCKETS) += virtio_transport.o
obj-$(CONFIG_VIRTIO_VSOCKETS_COMMON) += virtio_transport_common.o
CFLAGS_virtio_transport.o := -DDEBUG
CFLAGS_virtio_transport_common.o := -DDEBUG

vsock-y += af_vsock.o vsock_addr.o

vmw_vsock_vmci_transport-y += vmci_transport.o vmci_transport_notify.o \
	vmci_transport_notify_qstate.o
