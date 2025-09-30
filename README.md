Тут будут размещены playbooks для выполнения следующих задач:
Настроит базовый OS (apt-update, установит нужные пакеты like docker, kubeadm, kubectl, kubelet).
Настроит firewall, SSH, users.

Иницииализирует Kubernetes кластер на master-ноде и присоединит worker-ноды. (Ты это уже делал вручную — теперь автоматизируй!).
Установит Ingress-контроллер (например, Nginx Ingress) и MetalLB.
Используй Ansible Roles для организации плейбуков (roles для kubernetes, docker, base-setup
