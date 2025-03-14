---
title: 데이터 동기화 방법  
date: 2024-09-20  
ShowToc: true
copy_mark: src
---

기술적으로 말하자면, 우리 앱은 기기 간 데이터 동기화를 지원하지 않습니다. 백업 기능을 사용하여 데이터를 한 기기에서 다른 기기로 옮길 수는 있지만, 이를 동기화라고 부르기는 어렵습니다.

그렇긴 해도, 앱 외부에서 데이터를 동기화하는 몇 가지 방법이 있습니다.

# 앱의 홈 폴더로 저장소 폴더 설정

기기의 저장소에 폴더를 만들어 이를 앱의 홈 폴더로 설정할 수 있습니다. 이 경우, 책과 챕터는 해당 폴더 내의 하위 폴더 및 텍스트 파일로 저장됩니다.

이미 파일로 저장되어 있기 때문에 외부 파일 동기화 도구를 사용하여 기기 간 데이터를 동기화할 수 있습니다.

# [Syncthing](https://play.google.com/store/apps/details?id=com.nutomic.syncthingandroid)

Syncthing은 널리 사용되는 크로스 플랫폼 데이터 동기화 도구입니다. 이를 사용하여 휴대폰, PC, 노트북 또는 홈 서버 간에 앱의 데이터를 동기화할 수 있습니다.

Syncthing 공식 가이드를 확인하여 설정하는 방법을 알아보세요:

[Syncthing - 시작하기](https://docs.syncthing.net/intro/getting-started.html#getting-started)

# 네트워크 디스크

일부 네트워크 디스크는 양방향 파일 동기화 기능을 제공합니다. 앱의 홈 폴더를 동기화 폴더로 설정하면 기기 간 데이터를 동기화할 수 있으며, 이 경우 백업 서버로도 활용할 수 있습니다.

# Git, SVN, Rsync

프로그래밍 지식이 있는 사용자에게는 이 방법을 권장합니다. Termux와 같은 앱을 사용하여 명령줄 도구를 통해 데이터를 동기화할 수 있습니다.

Git, SVN 또는 Rsync에 익숙하다면 이 방법은 매우 유연한 옵션입니다. 그러나 이러한 도구를 잘 모른다면, 일반 사용자를 위한 방법이 아니기 때문에 권장하지 않습니다.

# 요약

앱의 주요 목적은 사용자의 데이터를 안전하게 보호하는 것입니다. 두 클라이언트 앱 간의 데이터 동기화는 항상 안전하지 않으므로, 내장 동기화 기능을 개발하지 않았습니다. 대신 신뢰할 수 있는 전문적인 도구를 사용하여 데이터를 동기화하는 것을 권장합니다.
