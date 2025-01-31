---
ShowToc: true
copy_mark: src
date: 2024-08-24
title: 如何找回資料
---

這篇指引將會告訴您如何找回您的資料，無論您認為您的資料丟失了或者想要在不同裝置間轉移資料，該篇指引都將提供必要的幫助。

## 從回收站中恢復資料

如果您是在應用內刪除了您的章節或者資料夾的話，這些資料不會被立即刪除而是會被移動到回收站，以防您之後希望撤銷刪除操作。

在回收站中的檔案將會被保持 30 天，之後才會被自動刪除，所以您無須擔心儲存空間佔用的問題。

請檢視這個影片以瞭解如何使用回收站功能：

{{< youtube id="WUrHmY4-T30" >}}

## 從快照中恢復您的資料

如果您在應用之外刪除了您的章節，比如您設定了一個裝置內建儲存的資料夾作為應用主頁並且使用一個檔案管理器刪掉了該資料夾中的部分章節，那麼在這種情況下您可以使用快照功能來恢復資料。

每次應用儲存您的章節時它都會額外建立一份儲存資料的快照。預設情況下每份每份檔案都會保持最多 30 份快照，新的快照建立的時候最舊的快照將會被刪除。

請檢視如下影片以瞭解如何使用快照功能：

{{< youtube id="QRlzmj-Vp88" >}}

## 從應用內部備份中恢復資料

應用內部備份機制會將應用主頁資料夾中的所有檔案打包成一個 zip 檔案並儲存到一個應用內部資料夾中。這個機制是預設啟用並且全自動的。

請檢視如下演示影片以瞭解如何從應用內部備份中恢復資料：

{{< youtube id="GAOLcbpsCHQ" >}}

## 從本地儲存備份中恢復資料

當您意外解除安裝本應用時這將是您恢復資料的主要手段。

上面所有提到的機制都是將資料儲存在應用內部的，但應用被解除安裝時這些資料將會被一併刪除。為了確保備份的資料能夠在解除安裝之後仍然可用，您需要設定您一個位於內建儲存空間的資料夾作為應用的儲存備份資料夾。當應用北部備份在打包備份資料的時候，應用將會一併複製一份 zip 檔案到您所設定的資料夾中。

請檢視如下演示影片以瞭解如何使用設定儲存備份：

{{< youtube id="Y-M5V3OKWM8" >}}

## 從雲備份伺服器中恢復資料：

上述提到的所有機制，包括儲存備份備份在內，都僅在單個裝置中運作。如果您丟失了您的裝置或者想要在多個裝置之間傳輸資料的話，您就需要用到雲備份服務。

請注意，雲備份服務僅在你曾按照應用引導下設定過才能正常工作。如果你曾經設定過的話，那麼恢復資料的操作會容易許多。

請檢查如下演示影片以瞭解如何透過雲備份服務來備份和恢復你的資料：

{{< youtube id="F2UTxySivO4" >}}

## Android 系統自動備份

我們從不推薦或者在任何應用簡介中提到該備份機制因為我們認為這不是一個可靠的機制，但對於從未設定雲備份服務又丟失了裝置並且想要找回資料的粗心使用者而言，這又是可能救回資料的最後一根稻草。

如果你曾在裝置上登入過 Google 賬號並且開啟了它的自動備份設定的話，那麼每間隔 24 小時 Android 系統就會檢查上面提到的應用內部備份的資料夾，並將其中的檔案上傳到你的 Google Drive 中的一個僅能夠由 Android 系統訪問的隱藏空間中。

但是請記住這個機制並不是那麼可靠的，如果你真的關心您的資料安全的話。

你可以檢視如下如下的樣式影片以瞭解它是如何運作的：

{{< youtube id="PMrsCCpMebk" >}}

請注意你無須每一步都按照影片中的去做，它僅僅是一個演示影片。你需要做的僅僅是在新裝置上安裝本應用，如果這個機制成功運作的話，在首次進入應用後你將會看到一個展示著舊備份資料的列表對話方塊，就像是演示影片展示的一樣。

## 總結

如你所見我們提供了諸多工具以保證你的資料安全和完整性，但是如果你從不關心這些的話，那沒人能夠意外發生的時候給你保證能夠找回所有資料。
