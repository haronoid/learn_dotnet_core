# learn_dotnet_core
dotnet core

#apt-getのソースリストにdotnetdev.listを追加する。
sudo sh -c 'echo "deb [arch=amd64] https://apt-mo.trafficmanager.net/repos/dotnet-release/ trusty main" > /etc/apt/sources.list.d/dotnetdev.list'<br/>
sudo apt-key adv --keyserver apt-mo.trafficmanager.net --recv-keys 417A0893<br/>
sudo apt-get update<br/>

#dotnet install<br/>
sudo apt-get install dotnet-dev-1.0.0-preview2-003121<br/>

#良く使う
dotnet new<br/>
dotnet restore<br/>
dotnet run<br/>

#その他
dotnet new : サンプル プロジェクトの生成 (C#, F#)<br/>
dotnet restore : 実行に必要なパッケージのリストア<br/>
dotnet build : .NET Core プロジェクトのビルド<br/>
dotnet publish : .NET アプリケーションの発行<br/>
dotnet run : .NET プロジェクトのビルドと実行<br/>
dotnet test : ユニットテストの実行<br/>
dotnet pack : アセンブリの NuGet パッケージ生成<br/>
dotnet [app.dll] : アプリケーションの実行<br/>
