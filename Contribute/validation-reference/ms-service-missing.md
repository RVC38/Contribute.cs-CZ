---
title: ms-service-missing
description: Vysvětlení a řešení problému sestavení ms-service-missing na webu Docs
author: meganbradley
ms.author: mbradley
ms.topic: error-reference
ms.date: 2/2/2019
ms.prod: non-product-specific
ms.openlocfilehash: 2bc425726f82840565978072b2efdf13a1284ec0
ms.sourcegitcommit: 203ca15fda2d217f082c74ec648c1f1db323f9f1
ms.translationtype: HT
ms.contentlocale: cs-CZ
ms.lasthandoff: 02/04/2019
ms.locfileid: "55713078"
---
# <a name="ms-service-missing"></a><span data-ttu-id="906b9-103">ms-service-missing</span><span class="sxs-lookup"><span data-stu-id="906b9-103">ms-service-missing</span></span>

<span data-ttu-id="906b9-104">**Připravujeme**</span><span class="sxs-lookup"><span data-stu-id="906b9-104">**Coming soon!**</span></span>

[!INCLUDE [suggestion-note](includes/suggestion-note.md)]

## <a name="suggestion"></a><span data-ttu-id="906b9-105">Návrh</span><span class="sxs-lookup"><span data-stu-id="906b9-105">Suggestion</span></span>

`Missing attribute: ms.service. If you specify ms.subservice, you must also specify ms.service.`

<span data-ttu-id="906b9-106">K zadání cloudových služeb používejte `ms.service`.</span><span class="sxs-lookup"><span data-stu-id="906b9-106">Use `ms.service` to specify cloud services.</span></span> <span data-ttu-id="906b9-107">Pokud chcete o `ms.service` zadat podrobnější informace, můžete volitelně zadat `ms.subservice`, ale pokud zadáte `ms.subservice`, musíte také zadat `ms.service`.</span><span class="sxs-lookup"><span data-stu-id="906b9-107">To specify more detailed information about `ms.service`, you can optionally specify `ms.subservice`, but if you specify `ms.subservice`, you must also specify `ms.service`.</span></span> <span data-ttu-id="906b9-108">Hodnoty `ms.service` a `ms.subservice` musí tvořit platnou dvojici.</span><span class="sxs-lookup"><span data-stu-id="906b9-108">The values for `ms.service` and `ms.subservice` must be a valid pair.</span></span>

## <a name="resolution"></a><span data-ttu-id="906b9-109">Řešení</span><span class="sxs-lookup"><span data-stu-id="906b9-109">Resolution</span></span>

<span data-ttu-id="906b9-110">Ujistěte se, jestli je vámi zadaná hodnota `ms.subservice` pro váš článek správná.</span><span class="sxs-lookup"><span data-stu-id="906b9-110">Confirm that the `ms.subservice` value you've specified is correct for your article.</span></span> <span data-ttu-id="906b9-111">Potom přidejte příslušnou hodnotu `ms.service`, která je platným nadřazeným objektem pro `ms.subservice`.</span><span class="sxs-lookup"><span data-stu-id="906b9-111">Then add the appropriate `ms.service` value that is a valid parent for the `ms.subservice`.</span></span>

<span data-ttu-id="906b9-112">Platné hodnoty se dají najít na [tomto interním webu Microsoftu](https://docsmetadatatool.azurewebsites.net/whitelists).</span><span class="sxs-lookup"><span data-stu-id="906b9-112">Valid values can be found on [this Microsoft-internal site](https://docsmetadatatool.azurewebsites.net/whitelists).</span></span>

<!--make sure to add this file to your includes folder and verify the path-->
[!INCLUDE [validation-reference-help](includes/validation-reference-help.md)]
