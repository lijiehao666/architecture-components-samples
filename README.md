Android Architecture Components 示例
===================================

[English](README.en.md)

一组使用 [Architecture Components](https://developer.android.com/arch) 的示例：

- [Room](https://developer.android.com/topic/libraries/architecture/room)
- [Lifecycle-aware components](https://developer.android.com/topic/libraries/architecture/lifecycle)
- [ViewModels](https://developer.android.com/topic/libraries/architecture/viewmodel)
- [LiveData](https://developer.android.com/topic/libraries/architecture/livedata)
    - [Paging](https://developer.android.com/topic/libraries/architecture/paging/)
    - [Navigation](https://developer.android.com/topic/libraries/architecture/navigation/)
    - [ViewBinding](https://developer.android.com/topic/libraries/view-binding)
    - [WorkManager](https://developer.android.com/topic/libraries/architecture/workmanager/)

### 示例

* **[BasicSample](BasicSample)** - 演示如何使用 SQLite 数据库和 Room 持久化数据，同时使用 ViewModels 和 LiveData。

* **[PersistenceContentProviderSample](PersistenceContentProviderSample)** - 演示如何使用 Room 通过 Content Provider 暴露数据。

* **[GithubBrowserSample](GithubBrowserSample)** - 一个**进阶**示例，使用 Architecture Components、Dagger 和 Github API，以 Kotlin 编写。

* **[BasicRxJavaSample](BasicRxJavaSample)** - 演示如何将 Room 与 RxJava 2 一起使用，同时使用 ViewModels。

* **[PersistenceMigrationsSample](PersistenceMigrationsSample)** - 演示如何在 Room 中实现数据库迁移。

* **[BasicRxJavaKotlinSample](BasicRxJavaSampleKotlin)** - 演示如何在 Kotlin 中将 ViewModels 和 Room 与 RxJava 一起使用。

 * **[PagingSample](PagingSample)** - 演示如何在 Kotlin 中将 Paging 库与 Room 一起使用。

 * **[PagingNetworkSample](PagingWithNetworkSample)** - 演示如何在 Kotlin 中通过 Retrofit 将 Paging 库与后端 API 一起使用。

* **[NavigationBasicSample](NavigationBasicSample)** - 演示如何在 Kotlin 中使用 Navigation 进行页面跳转和深层链接。

* **[NavigationAdvancedSample](NavigationAdvancedSample)** - 演示如何使用 Navigation 和 BottomNavigationView 处理多个返回栈。

* **[LiveDataSample](LiveDataSample)** - 演示如何将 Kotlin 协程与 `LiveData` 等 Architecture Components 集成。

* **[ViewBindingSample](ViewBindingSample)** - 演示如何在 Activity 和 Fragment 中使用 View Binding。

* **[WorkManagerSample](WorkManagerSample)** - 演示如何在 Kotlin 中使用 WorkManager 处理后台任务。

### 中文本地化

各示例应用已提供简体中文（`values-zh-rCN`）字符串资源。在系统语言为简体中文的设备上，界面会自动显示中文；其他语言环境仍使用默认英文文案。

### 反馈问题

你可以在本仓库提交 [Issue](https://github.com/googlesamples/android-architecture-components/issues)。如果发现问题出在 Architecture Components 本身，请使用 [Architecture Components Issue Tracker](https://issuetracker.google.com/issues/new?component=197448&template=878802) 反馈。

License
-------

Copyright 2018 The Android Open Source Project, Inc.

Licensed to the Apache Software Foundation (ASF) under one or more contributor
license agreements.  See the NOTICE file distributed with this work for
additional information regarding copyright ownership.  The ASF licenses this
file to you under the Apache License, Version 2.0 (the "License"); you may not
use this file except in compliance with the License.  You may obtain a copy of
the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS, WITHOUT
WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.  See the
License for the specific language governing permissions and limitations under
the License.
