---
aliases:
- /es/real_user_monitoring/reactnative/data_collected/
code_lang: reactnative
code_lang_weight: 40
description: Obtén información sobre los datos recopilados por la monitorización de
  React Native.
further_reading:
- link: https://github.com/DataDog/dd-sdk-reactnative
  tag: Código fuente
  text: Código fuente de dd-sdk-reactnative
- link: real_user_monitoring/explorer/
  tag: Documentación
  text: Aprender a explorar tus datos de RUM
- link: real_user_monitoring/guide/monitor-hybrid-react-native-applications
  tag: Documentación
  text: Monitorizar aplicaciones híbridas de React Native
title: Datos recopilados de RUM React Native
type: multi-code-lang
---
## Información general

El SDK de Datadog React Native para RUM genera eventos con métricas y atributos asociados. Las métricas son valores cuantificables que pueden utilizarse para mediciones relacionadas con el evento. Los atributos son valores no cuantificables que se utilizan para segmentar los datos de métricas (agrupar por) en el RUM Explorer.

La mayoría de los datos de monitorización de React Native son recopilados por los SDKs nativos de Datadog iOS y Android para RUM, y se conservan durante los mismos periodos.

* Para métricas y atributos específicos de eventos de iOS, consulta [datos recopilados de RUM iOS][1].
* Para conocer los atributos y métricas específicos de eventos de Android, consulta [datos recopilados de RUM Android][2].

## Lectura adicional

{{< partial name="whats-next/whats-next.html" >}}

[1]: /es/real_user_monitoring/ios/data_collected/#event-specific-metrics-and-attributes
[2]: /es/real_user_monitoring/android/data_collected/#event-specific-metrics-and-attributes