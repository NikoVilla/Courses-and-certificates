📜 Certificados de Cursos – CV

Este repositorio contiene los certificados de cursos y formaciones que respaldan mi curriculum vitae.

📧 Contacto

Si necesitas más información, puedes contactarme en:
- Linkedin: [https://www.linkedin.com/in/villamolef/](https://www.linkedin.com/in/villamolef/)

Para resolver esto, aplica lo siguiente:
- Arranca NETinVM.
- En "base", como "user1", ejecuta:

   m=exte; virt-xml $m --edit --xml /domain/@type='qemu' ; virt-xml $m
--edit --cpu qemu64

   Esta orden cambia el hipervisor de "kvm" (necesita soporte hardware
para virtualización anidada) a "qemu" (usa emulación de hardware y no
necesita soporte hardware para la virtualización).

- Prueba a ponerla en marcha:

   netinvm_run exte

- Si todo va bien (hay que tener paciencia), apaga "exte" y repite la
orden para todas las máquinas que vayas a usar (o todas).
