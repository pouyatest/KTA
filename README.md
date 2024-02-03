# Arch Install
### Commands
> timedatectl

> mount /dev/root_partition /mnt

> pacstrap -K /mnt base linux linux-firmware git nano

> genfstab -U /mnt >> /mnt/etc/fstab

> arch-chroot /mnt

> ln -sf /usr/share/zoneinfo/Region/City /etc/localtime

> hwclock --systohc
### Edit /etc/locale.gen
> locale-gen
