---
title: Xamarin.Forms 지역화
description: 기본 제공.NET 지역화 프레임 워크 Xamarin.Forms 사용한 플랫폼 간 다국어 응용 프로그램을 만드는 데 사용할 수 있습니다. 텍스트 및 이미지를 지역화할 수 있는 및 응용 프로그램은 오른쪽에서 왼쪽 방향을 지원할 수 있습니다.
ms.prod: xamarin
ms.assetid: 97BF843B-BDAA-4CEA-8189-6DB54B291D7F
ms.technology: xamarin-forms
author: davidbritch
ms.author: dabritch
ms.date: 04/13/2018
ms.openlocfilehash: 78731924324a1ddd34c0d197070699e2998c1513
ms.sourcegitcommit: 66682dd8e93c0e4f5dee69f32b5fc5a96443e307
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 06/08/2018
ms.locfileid: "35240595"
---
# <a name="xamarinforms-localization"></a>Xamarin.Forms 지역화

_기본 제공.NET 지역화 프레임 워크 Xamarin.Forms 사용한 플랫폼 간 다국어 응용 프로그램을 만드는 데 사용할 수 있습니다._

## <a name="string-and-image-localizationtextmd"></a>[문자열 및 이미지 지역화](text.md)

.NET 응용 프로그램 사용 하 여 지역화를 위한 기본 제공 메커니즘 [RESX 파일](http://msdn.microsoft.com/library/ekyft91f(v=vs.90).aspx) 와의 클래스는 `System.Resources` 및 `System.Globalization` 네임 스페이스입니다. RESX 파일 번역 된 문자열을 포함 하는 번역에 대 한 강력한 형식의 액세스를 제공 하는 컴파일러에서 생성 된 클래스와 함께 Xamarin.Forms 어셈블리에 포함 됩니다. 코드에서 번역된 된 텍스트를 검색할 수 있습니다.

## <a name="right-to-left-localizationright-to-leftmd"></a>[오른쪽에서 왼쪽으로 지역화](right-to-left.md)

흐름 방향은 눈 하 여 페이지의 UI 요소 ֻ 방향입니다. 오른쪽에서 왼쪽으로 지역화 Xamarin.Forms 응용 프로그램에 오른쪽에서 왼쪽 방향에 대 한 지원을 추가합니다.
