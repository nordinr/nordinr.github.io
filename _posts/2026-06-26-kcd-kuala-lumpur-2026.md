---
title: KCD Kuala Lumpur 2026
date: 2026-06-27
permalink: /posts/2026/06/kcd-kuala-lumpur-2026/
tags:
  - Kubernetes
  - Cloud Native
  - DevOps
  - Observability
---

![](/images/uploads/img_4436.jpeg "Reunion bersama kawan-kawan yang kita suka")

# KCD Kuala Lumpur 2026: Isyarat Matangnya Komuniti Cloud Native Malaysia

Perjalanan ke Kuala Lumpur kali ini bukan sekadar menghadiri satu lagi acara teknologi. Kubernetes Community Day (KCD) Kuala Lumpur 2026 membawa makna yang lebih besar kerana ia menjadi sebahagian daripada gerakan komuniti cloud native tempatan yang semakin matang. Acara ini berlangsung pada 27 Jun 2026 di The iSpace @ Plaza Vads, TTDI, Kuala Lumpur, dari 9 pagi hingga 6 petang.

Apa yang menarik, KCD bukan acara vendor semata-mata. Ia dibentuk oleh komuniti, untuk komuniti. Fokusnya jelas: Kubernetes, cloud native, open source, observability, networking, real-world case studies dan perkongsian pengalaman daripada pengamal yang benar-benar membina serta mengendalikan sistem.

## Kubernetes Bukan Lagi Sekadar Cluster

Dulu, perbincangan Kubernetes banyak berlegar sekitar soalan asas: bagaimana hendak deploy Pod, expose Service, atau tulis YAML yang betul. Tetapi dalam ekosistem hari ini, Kubernetes sudah bergerak jauh daripada sekadar tempat menjalankan container.

Kubernetes kini menjadi lapisan operasi untuk membina platform. Di atasnya kita mula bercakap tentang GitOps, policy, observability, security, autoscaling, service mesh, networking dan developer experience. Soalan yang lebih penting bukan lagi "boleh deploy atau tidak?", tetapi:

- Adakah deployment itu boleh diulang dengan konsisten?
- Adakah perubahan dapat dijejak melalui Git?
- Adakah pasukan boleh rollback dengan yakin?
- Adakah sistem memberi signal yang cukup apabila berlaku masalah?
- Adakah developer boleh menghantar perubahan tanpa perlu memahami semua kerumitan infra?

Di sinilah nilai acara seperti KCD terasa. Ia mengingatkan bahawa Kubernetes bukan teknologi yang berdiri sendiri. Ia adalah sebahagian daripada sistem kerja yang lebih besar.

## Observability Sebagai Asas Keyakinan

Salah satu topik yang semakin penting dalam dunia cloud native ialah observability. Dalam sistem moden, log sahaja tidak cukup. Kita perlukan metric, trace, alert dan konteks yang boleh membantu pasukan memahami tingkah laku sistem.

Apabila aplikasi berjalan dalam Kubernetes, masalah jarang berlaku pada satu lapisan sahaja. Kadang-kadang ia bermula daripada konfigurasi resource, kadang-kadang daripada network policy, ingress, DNS, storage, image pull, dependency luaran atau perubahan kecil dalam deployment. Tanpa observability yang baik, troubleshooting akan berubah menjadi kerja meneka.

Sebab itu, bagi saya, kematangan sesebuah pasukan DevOps atau platform engineering boleh dilihat daripada cara mereka menjawab incident. Pasukan yang matang bukan sekadar bertanya siapa yang deploy, tetapi melihat signal teknikal: apa yang berubah, bila ia berubah, komponen mana yang terkesan, dan bagaimana kesannya kepada pengguna.

## GitOps Dan Disiplin Operasi

KCD juga menguatkan semula satu prinsip penting: automation tanpa disiplin hanya akan mempercepatkan kekacauan. Dalam ekosistem Kubernetes, GitOps menjadi pendekatan yang masuk akal kerana ia menjadikan Git sebagai sumber kebenaran untuk konfigurasi sistem.

Dengan GitOps, perubahan kepada cluster tidak sepatutnya berlaku secara rawak melalui arahan manual yang sukar dijejak. Sebaliknya, perubahan perlu melalui commit, review, pipeline dan controller seperti Argo CD atau Flux. Pendekatan ini bukan sekadar memudahkan deployment, tetapi membantu pasukan membina audit trail dan mengurangkan risiko konfigurasi drift.

Untuk organisasi yang masih bergantung kepada deployment manual, inilah antara lompatan budaya yang paling mencabar. Tool boleh dipasang dalam sehari, tetapi disiplin operasi memerlukan latihan dan persetujuan pasukan.

## Komuniti Sebagai Infrastruktur Tidak Nampak

Bahagian paling bernilai daripada acara komuniti seperti KCD bukan hanya sesi teknikal di pentas. Nilainya juga ada pada perbualan di luar sesi: bertanya pengalaman orang lain, melihat bagaimana organisasi lain menyusun platform, dan menyedari bahawa masalah yang kita hadapi sebenarnya dikongsi oleh ramai pengamal lain.

![](/images/uploads/img_4498.jpeg)

Dalam dunia cloud native, komuniti adalah satu bentuk infrastruktur yang tidak nampak. Dokumentasi rasmi memberi asas, tetapi pengalaman komuniti membantu kita memahami realiti production: apa yang mudah di atas kertas, apa yang sukar bila diskalakan, dan apa yang perlu dielakkan sebelum ia menjadi hutang operasi.

## Apa Yang Saya Bawa Pulang

Ada beberapa perkara yang saya rasa penting selepas menghadiri KCD Kuala Lumpur 2026:

1. Kubernetes perlu dilihat sebagai platform operasi, bukan sekadar runtime container.
2. Observability perlu dibina dari awal, bukan ditambah selepas incident besar berlaku.
3. GitOps membantu pasukan mengurus perubahan dengan lebih konsisten dan boleh diaudit.
4. Komuniti tempatan semakin penting untuk membina bakat cloud native Malaysia.
5. Open source bukan sekadar menggunakan software percuma, tetapi berkongsi pengetahuan dan membina amalan bersama.

![](/images/uploads/img_4457.jpeg)

Sebagai pengamal DevOps, acara seperti ini memberi ruang untuk menilai semula cara kita bekerja. Adakah pipeline kita benar-benar membantu? Adakah monitoring kita cukup berguna? Adakah deployment kita boleh dipercayai? Adakah platform yang kita bina memudahkan pasukan lain, atau menambah lapisan kerumitan baru?

KCD Kuala Lumpur 2026 menunjukkan bahawa ekosistem cloud native di Malaysia sedang bergerak ke arah yang lebih matang. Ia bukan lagi sekadar mengikuti trend global, tetapi mula membina ruang tempatan untuk belajar, berkongsi dan meningkatkan standard operasi.

![](/images/uploads/img_4427.jpeg)

Semoga lebih banyak sesi seperti ini diteruskan, dan semoga komuniti cloud native Malaysia terus berkembang dengan lebih terbuka, praktikal dan teknikal.

Rujukan:
- [KCD Kuala Lumpur 2026 - CNCF](https://community2.cncf.io/events/details/cncf-kcd-kuala-lumpur-2026-presents-kcd-kuala-lumpur-2026/)
- [KCD Kuala Lumpur 2026 - Humanitix](https://events.humanitix.com/kcd-kuala-lumpur-2026)
- [KCD Kuala Lumpur 2026 - Sessionize](https://sessionize.com/kcd-kuala-lumpur-2026/)
