---
title: ms-author-invalid
description: Vysvětlení a řešení problému sestavení ms-author-invalid na webu Docs
author: meganbradley
ms.author: mbradley
ms.topic: error-reference
ms.date: 2/28/2019
ms.prod: non-product-specific
ms.openlocfilehash: 25428f93eaa7d36a5bbe35d77434ef33972e8944
ms.sourcegitcommit: dd751d0cb5b11f81a64ef62f3c83fd17cc5f0541
ms.translationtype: HT
ms.contentlocale: cs-CZ
ms.lasthandoff: 09/03/2019
ms.locfileid: "70236531"
---
# <a name="ms-author-invalid"></a>ms-author-invalid

## <a name="warning"></a>Upozornění

`Invalid value for ms.author: '{value}' is not a valid Microsoft alias, or is not an allowed distribution list.`

## <a name="resolution"></a>Řešení

Ověřte, že hodnota `ms.author` je platný alias Microsoftu aktuálního autora. Pokud je tento alias distribučním seznamem, musí být také na seznamu povolených.

Platné hodnoty pro distribuční seznamy se dají najít na [tomto interním webu Microsoftu](https://docsmetadatatool.azurewebsites.net/allowlists).

<!--make sure to add this file to your includes folder and verify the path-->
[!INCLUDE [validation-reference-help](includes/validation-reference-help.md)]
