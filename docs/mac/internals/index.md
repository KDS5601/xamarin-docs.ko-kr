---
title: Xamarin.Mac에서는
description: 이 문서는 Xamarin.Mac의 내부 작업을 설명 하는 다양 한 설명서를 링크 합니다. 미리 컴파일, Xamarin.Mac 아키텍처 및 Xamarin.Mac 등록자 연결 된 문서에 설명합니다.
ms.prod: xamarin
ms.assetid: 84974D75-0CCE-4455-AA38-00DE68AE33B6
ms.technology: xamarin-mac
author: bradumbaugh
ms.author: brumbaug
ms.date: 11/10/2017
ms.openlocfilehash: c940252a675c38247d2c5bb374b9c30237222bda
ms.sourcegitcommit: ea1dc12a3c2d7322f234997daacbfdb6ad542507
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 06/05/2018
ms.locfileid: "34792491"
---
# <a name="under-the-hood-in-xamarinmac"></a>Xamarin.Mac에서는

## <a name="ahead-of-time-compilation-aotaotmd"></a>[컴파일 (AOT) 앞의](aot.md)

미리 (AOT) 시간의 컴파일은 시작 성능을 향상 시키기 위한는 강력한 최적화 기술입니다. 그러나 것도 영향을 줍니다 빌드 시간, 응용 프로그램 크기 및 프로그램 실행, 미 방식에서 작동 방식을 이해 있으므로 합니다.

## <a name="mac-architecturearchitecturemd"></a>[Mac 아키텍처](architecture.md)

Objective-c, 컴파일, 선택기, 등록, 앱 시작 및 생성자와 같은 개념을 비롯 한 Xamarin.Mac의 관계입니다.

## <a name="xamarinmac-registrarregistrarmd"></a>[Xamarin.Mac 등록자](registrar.md)

Xamarin.Mac는 Cocoa의 런타임, 관리 되지 않는 Objective-c 클래스를 호출 하는 이벤트가 발생할 때 호출할 수 있는 관리 되는 클래스를 허용 하 고 관리 되는 환경 사이의 간격을 잇는 합니다. 이 "매직"를 수행 하는 데 필요한 작업은 등록 기관에 의해 처리 됩니다 하지만 "내부"에서 진행 상황을 이해 경우가 유용할 수 있습니다.
