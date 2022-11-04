---
title: "Moduli personalizzati: La funzione HOUR nei campi calcolati utilizza UTC"
description: "Quando un campo calcolato include la funzione HOUR, la funzione restituisce valori basati su UTC anziché sul fuso orario previsto. Pertanto, qualsiasi calcolo basato sul valore HOUR non è corretto."
hidefromtoc: true
source-git-commit: a681d8afd4bcf1ddfccf192871442e63dae1b2c3
workflow-type: tm+mt
source-wordcount: '90'
ht-degree: 4%

---


# Moduli personalizzati: [!UICONTROL ORA] funzione nei campi calcolati utilizza UTC

>[!NOTE]
>
>Questo problema è stato risolto il 3 novembre 2022.

Quando un campo calcolato include [!UICONTROL ORA] funzione , la funzione restituisce valori basati su UTC anziché sul fuso orario previsto. Pertanto, qualsiasi calcolo basato sul valore HOUR non è corretto.

_Segnalato per la prima volta il 17 ottobre 2022._

