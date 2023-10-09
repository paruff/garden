
It supports Docker, which is enough to run your Sonarr, Transmission, or HomeAssistant. You don't need k8s for that.

That said, if you want to poke around and learn k8s, you can run [minikube](https://minikube.sigs.k8s.io/docs/), but it's not a breeze. It won't work with the "docker" driver as the builtin Docker is using brtfs, which causes problems. Only way I managed is by using the "qemu" driver. here's how:

- install Linuxbrew as I explained here [https://community.synology.com/enu/forum/1/post/153781](https://community.synology.com/enu/forum/1/post/153781)
    
- install minikube and qemu using Linuxbrew: `brew install minikube qemu`Warning: this will download a bunch of dependencies, so don't be in a hurry. Note: If you have installed "Virtual machine Manager" through the Package Center, qemu is already there, but it's a stripped down and customized version that is unusable for this purpose.
    
- Give permissions to /dev/kvm: `chmod 666 /dev/kvm`
    
- Start minikube like this: `minikube start --driver=qemu --qemu-firmware-path=/usr/share/qemu/OVMF_CODE.fd`
    
- Enjoy!

From https://www.reddit.com/r/synology/comments/t3o4le/is_the_synology_nas_able_to_run_a_kubernetes/?rdt=52810