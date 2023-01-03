# VXLan Fix for kubernetes

## Запуск

```
ansible-playbook -i path_to_inventory -e 'k8s_hosts=host-group'
```

## Переменнные

`vxlan_interface` - интерфейс VXLAN
Например:
* vxlan.calico для Calico
* flannel.1 для Flannel

Определяется автоматически

