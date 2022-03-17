# C#Server-Packet送、受信

## 1.環境
> Visual Studio 2022 : C#

## 2.機能
> ClientとサーバーのPacket送、受信テスト

## 3.概要
> 掲示板システムを作る前にUnityでサーバープロジェクト始めるために作成しました。<br>
> 簡単にDummyClientとサーバーと文字をserializeし送信、受信を行うプログラムです。<br>


#### **実行するには下記を読んでください** 
> プロジェクトをダウンロードした後<br>
> 1.まずサーバープログラムを起動-待機　(...AutoPacket\Server\bin\Debug\netcoreapp3.1\Server.exe)<br>
> 2.その後DummyClientを起動-信号を送る　(...AutoPacket\DummyClient\bin\Debug\netcoreapp3.1\DummyClient.exe)<br>
> Packet通信に成功した後、時間が過ぎて通信終了になります。

## Player情報をSerializationをしているコード
(https://github.com/YongGwang/SeverStudy/blob/main/AutoPacket/PacketGenerator/PacketFormat.cs)

## PacketFormatを決めているコード
(https://github.com/YongGwang/SeverStudy/blob/main/AutoPacket/PacketGenerator/PacketFormat.cs)

## 自動生成されたコード
(https://github.com/YongGwang/SeverStudy/blob/main/AutoPacket/Server/Packet/GenPackets.cs)<br>
(https://github.com/YongGwang/SeverStudy/blob/main/AutoPacket/DummyClient/Packet/GenPackets.cs)<br>
