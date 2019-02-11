---
title: ms-prod-service-mismatch
description: Vysvětlení a řešení problému sestavení ms-prod-service-mismatch na webu Docs
author: meganbradley
ms.author: mbradley
ms.topic: error-reference
ms.date: 1/15/2019
ms.prod: non-product-specific
ms.openlocfilehash: 4a3cf8bc5435972f0442ca1d41d4147e1ea00d78
ms.sourcegitcommit: 203ca15fda2d217f082c74ec648c1f1db323f9f1
ms.translationtype: HT
ms.contentlocale: cs-CZ
ms.lasthandoff: 02/04/2019
ms.locfileid: "55713170"
---
# <a name="ms-prod-service-mismatch"></a><span data-ttu-id="8e13d-103">ms-prod-service-mismatch</span><span class="sxs-lookup"><span data-stu-id="8e13d-103">ms-prod-service-mismatch</span></span>

<span data-ttu-id="8e13d-104">**Připravujeme**</span><span class="sxs-lookup"><span data-stu-id="8e13d-104">**Coming soon!**</span></span>

[!INCLUDE [suggestion-note](includes/suggestion-note.md)]

## <a name="suggestion"></a><span data-ttu-id="8e13d-105">Návrh</span><span class="sxs-lookup"><span data-stu-id="8e13d-105">Suggestion</span></span>

`Invalid attribute pair: ms.prod and ms.subservice. You can only pair ms.prod with ms.technology.`

`Invalid attribute pair: ms.service and ms.technology. You can only pair ms.service with ms.subservice.`

<span data-ttu-id="8e13d-106">K zadání místních produktů používejte `ms.prod`, pro cloudové služby používejte `ms.service`.</span><span class="sxs-lookup"><span data-stu-id="8e13d-106">Use `ms.prod` to specify on-premises products; `ms.service` for cloud services.</span></span> <span data-ttu-id="8e13d-107">Pokud chcete o `ms.prod` zadat podrobnější informace, můžete volitelně zadat `ms.technology`.</span><span class="sxs-lookup"><span data-stu-id="8e13d-107">To specify more detailed information about `ms.prod`, you can optionally specify `ms.technology`.</span></span> <span data-ttu-id="8e13d-108">Pokud chcete o `ms.service` zadat podrobnější informace, můžete zadat `ms.subservice`.</span><span class="sxs-lookup"><span data-stu-id="8e13d-108">To specify more detailed information about `ms.service`, you can specify `ms.subservice`.</span></span> <span data-ttu-id="8e13d-109">Nemůžete použít `ms.prod` s `ms.subservice` ani `ms.service` s `ms.technology`.</span><span class="sxs-lookup"><span data-stu-id="8e13d-109">You can't use `ms.prod` with `ms.subservice` or `ms.service` with `ms.technology`.</span></span>

## <a name="resolution"></a><span data-ttu-id="8e13d-110">Řešení</span><span class="sxs-lookup"><span data-stu-id="8e13d-110">Resolution</span></span>

<span data-ttu-id="8e13d-111">Nejdříve ověřte, jestli jste pro váš článek vybrali správný nadřazený atribut (`ms.prod` nebo `ms.service`).</span><span class="sxs-lookup"><span data-stu-id="8e13d-111">First, verify that you have selected the correct parent attribute (`ms.prod` or `ms.service`) for your article.</span></span> <span data-ttu-id="8e13d-112">Pak přidejte patřičné podřízené pole s platnou spárovanou hodnotou.</span><span class="sxs-lookup"><span data-stu-id="8e13d-112">Then, add the appropriate child field with a valid paired value.</span></span> <span data-ttu-id="8e13d-113">Odeberte všechna nadbytečná pole.</span><span class="sxs-lookup"><span data-stu-id="8e13d-113">Remove any extra fields.</span></span>

<span data-ttu-id="8e13d-114">Platné hodnoty se dají najít na [tomto interním webu Microsoftu](https://docsmetadatatool.azurewebsites.net/whitelists).</span><span class="sxs-lookup"><span data-stu-id="8e13d-114">Valid values can be found on [this Microsoft-internal site](https://docsmetadatatool.azurewebsites.net/whitelists).</span></span>

<!--make sure to add this file to your includes folder and verify the path-->
[!INCLUDE [validation-reference-help](includes/validation-reference-help.md)]
