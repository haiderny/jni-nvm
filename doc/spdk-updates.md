��ǩ: SPDK

# SPDK��������

��Ҫ����[^1]������

* �����û���I/OAT������`lib/ioat`����֧�ֶ�ӦXeonƽ̨��DMA���濽��ж�ء�

  �û���I/OAT֧�ֵļ��룬Ҳʹ��SPDK�ĸ�����ӳ�ʵ����������NVMe��

* �淶��`nvme_spec.h`��

  - ���NVMe�������ڴ滺�嶨�塣

  - ���namespace����ö�ٶ��塣

* API��`include/spdk/nvme.h`��`include/spdk/vtophys.h`�ȣ�

  - ���й���API���`spdk_`ǰ׺��

  - ���ֹ���API�ع������������豸ʱ��ͨ��`spdk_nvme_probe()`��������ʽ����`libpciaccess`��API��

  - ������˽��API������

  ���˸о�SPDK��API��λ��ֻ����Ǻ����ƣ���ЩAPI�Ķ�λ���Ƚ�ģ�������Źٷ��������������

* PCI���ÿռ���ʽӿڣ�`include/spdk/pci.h`��

  - �ṩ���ֽ��밴�ֶ�д�Ľӿڡ�

  - PCI���͡���ʶ�ȵĶ���������`include/spdk/pci_ids.h`��

* ���ýű���`scripts/`��

  - ��Ӷ�vfio���õ�֧�֡�

  - ԭ`cleanup.sh`��`unbind.sh`����Ϊһ��`setup.sh`�ű�������ָ�ʹ���ں�������ʹ�ò���`reset`���ɡ�

  - ������/�����ͨ�����ֱ�����`rmmod nvme`������ͨ������`/sys/bus/pci`����ʵ�֡�
    
* ����

  - DPDK-2.2.0�������䡣

  - ��������������Bug������

[^1]: ��`commit 9322c25`֮��ĸ��¡�