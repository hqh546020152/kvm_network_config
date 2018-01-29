# kvm_network_config

#default.xml#
default.xml为kvm默认网卡default.xml配置信息
备注：此配置在宿主机/etc/libvirt/qemu/networks目录下。

#ifcfg-br0#
ifcfg-br0为虚拟桥接网卡配置文件
备注：在宿主机/etc/sysconfig/network-scripts/下新建ifcfg-br0并填入以上信息。网卡类型：桥接、IP、网关地址。

#ifcfg-ens33#
ifcfg-ens33为宿主机实体网卡配置文件
备注：修改宿主机的网卡配置，填写网卡地址，并详明桥接的网卡

#ifcfg-eth0#
ifcfg-eth0为虚拟机网卡配置文件
备注：IP获取方式采取dhcp即可。
