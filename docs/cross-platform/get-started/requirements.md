---
title: 시스템 요구 사항
description: 이 문서에서는 Mac 및 Windows 컴퓨터에 Xamarin을 사용하여 앱을 빌드하기 위한 시스템 요구 사항을 나열합니다. 설치 지침으로 연결합니다.
ms.prod: xamarin
ms.assetid: dd344d57-18e2-42a5-8c15-3f5be4123c72
author: asb3993
ms.author: amburns
ms.date: 08/28/2017
ms.openlocfilehash: 04db2fe4e3385c55ecf653b002b909f16e99a101
ms.sourcegitcommit: ea1dc12a3c2d7322f234997daacbfdb6ad542507
ms.translationtype: HT
ms.contentlocale: ko-KR
ms.lasthandoff: 06/05/2018
ms.locfileid: "34780726"
---
# <a name="system-requirements"></a>시스템 요구 사항

_Xamarin 사용을 위한 필수 구성 요소_

Xamarin 제품은 Apple 및 Google의 플랫폼 SDK를 사용하여 iOS 또는 Android를 대상으로 설계되었으므로 시스템 요구 사항이 Microsoft와 일치합니다. 이 페이지에서는 Xamarin 플랫폼의 시스템 호환성과 권장 개발 환경 및 SDK 버전을 간략히 설명합니다.

- [개발 환경](#devenv)
- [macOS 요구 사항](#mac)
- [Windows 요구 사항](#windows)

소프트웨어 및 필요한 SDK를 받는 방법에 대한 자세한 내용은 [설치 지침](#install)을 참조하세요.

<a name="devenv" />

## <a name="development-environments"></a>개발 환경

이 표는 다양한 개발 도구 및 운영 체제 조합으로 개발할 수 있는 플랫폼을 보여줍니다.

[!include[](~/cross-platform/includes/development-environment.md)]


> [!NOTE]
> Windows 컴퓨터에서 iOS용으로 개발하려면 원격 컴파일 및 디버깅을 위해 [네트워크에서 액세스할 수 있는 Mac 컴퓨터](~/ios/get-started/installation/windows/connecting-to-mac/index.md)가 있어야 합니다. 또한 Mac 컴퓨터의 Windows VM 내에서 실행 중인 Visual Studio가 있는 경우에도 개발이 가능합니다.

<a name="mac" />

## <a name="macos-requirements"></a>macOS 요구 사항

Xamarin 개발에 Mac 컴퓨터를 사용하려면 다음 소프트웨어/SDK 버전이 필요합니다. 운영 체제 버전을 확인하고 [Xamarin 설치 관리자](#install)의 지침을 따르세요.

[!include[](~/cross-platform/includes/macos-requirements.md)]

> [!NOTE]
> Xcode는 [developer.apple.com](https://developer.apple.com/xcode/download/) 또는 Mac App Store를 통해 설치(및 업데이트)할 수 있습니다.

### <a name="testing--debugging-on-macos"></a>masOS에서 테스트 및 디버깅

테스트하고 디버깅할 Xamarin 모바일 응용 프로그램을 USB를 통해 실제 장치에 배포할 수 있습니다(Xamarin.Mac 앱은 개발 컴퓨터에서 직접 테스트할 수 있으며, Apple Watch 앱은 연결된 iPhone에 먼저 배포됨).

[!include[](~/cross-platform/includes/macos-testing.md)]


<a name="windows" />

## <a name="windows-requirements"></a>Windows 요구 사항

Xamarin 개발에 Windows 컴퓨터를 사용하려면 다음 소프트웨어/SDK 버전이 필요합니다.
운영 체제 버전을 확인하세요. (그리고 Visual Studio의 *Express* 버전을 사용하고 있지 않은지 확인하세요. 그렇다면 *Community* 버전으로 업데이트하는 것이 좋습니다.)
Visual Studio 2015 및 2017 설치 관리자에는 자동으로 Xamarin을 설치하는 옵션이 있습니다.

[!include[](~/cross-platform/includes/windows-requirements.md)]


> [!NOTE]
>
>* Visual Studio용 Xamarin은 모든 Visual Studio 2015 또는 2017(Community, Professional 및 Enterprise)을 지원합니다.
>
>* UWP(유니버설 Windows 플랫폼)용 Xamarin.Forms 앱을 개발하려면 Visual Studio 2015 또는 2017이 설치된 Windows 10이 필요합니다.


### <a name="testing--debugging-on-windows"></a>Windows에서 테스트 및 디버깅

테스트하고 디버깅할 Xamarin 모바일 응용 프로그램을 USB를 통해 실제 장치에 배포할 수 있습니다(iOS 장치는 Visual Studio를 실행 중인 컴퓨터가 아니라, Mac 컴퓨터에 연결해야 함).

[!include[](~/cross-platform/includes/windows-testing.md)]


> [!NOTE]
>
>* [Windows Phone 8.1 에뮬레이터 다운로드](https://www.microsoft.com/download/details.aspx?id=43719).
>* Windows Phone 10 에뮬레이터는 Visual Studio 2015 UWP SDK에 포함되어 있습니다.

<a name="install" />

## <a name="installation-instructions"></a>설치 지침

macOS용 최신 Xamarin 릴리스는 [xamarin.com/download](http://xamarin.com/download)에서 다운로드할 수 있습니다. Windows의 경우, [Visual Studio 2017](https://docs.microsoft.com/visualstudio/install/install-visual-studio) 설치 지침을 따릅니다.

현재 제품 버전의 전체 목록은 [현재 릴리스 페이지](http://developer.xamarin.com/releases/current/)에서 볼 수 있습니다. 또한 이 페이지에는 베타 및 알파 채널의 개별 제품 버전(및 릴리스 정보에 대한 링크)도 간략하게 나와 있습니다.

각 플랫폼에 대한 자세한 [설치](~/cross-platform/get-started/installation/index.md) 지침은 여기에서 볼 수 있습니다.

- [Xamarin.iOS](~/ios/get-started/installation/index.md)
- [Xamarin.Android](~/android/get-started/installation/index.md)
- [Xamarin.Mac](~/mac/get-started/installation.md)

또한 [Xamarin.Forms 요구 사항 및 지원되는 플랫폼](~/xamarin-forms/get-started/installation.md)에 대한 추가 정보가 있습니다.


## <a name="related-links"></a>관련 링크

- [Xamarin 다운로드](https://xamarin.com/download/)
- [현재 릴리스](https://developer.xamarin.com/releases/current/)
