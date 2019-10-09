# gentoo_portage
portage stuff
to be used after invoking `# binutils-config --linker ld.gold`
special thanks to the people and wiki pages who influenced this:
 - https://wiki.gentoo.org/wiki/Project:LibreSSL
 - http://yuguangzhang.com/blog/enabling-gcc-graphite-and-lto-on-gentoo/
 - https://github.com/InBetweenNames/gentooLTO
 - https://gitgud.io/cloveros

Included is a script, forked from cloveros, for building kernels and initramfs while with ld.bfd while reverting to ld.gold at end of the creation process.  
