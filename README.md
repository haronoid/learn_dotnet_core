# learn_dotnet_core
dotnet core

#apt-getのソースリストにdotnetdev.listを追加する。
sudo sh -c 'echo "deb [arch=amd64] https://apt-mo.trafficmanager.net/repos/dotnet-release/ trusty main" > /etc/apt/sources.list.d/dotnetdev.list'
sudo apt-key adv --keyserver apt-mo.trafficmanager.net --recv-keys 417A0893
sudo apt-get update

#dotnet install
sudo apt-get install dotnet-dev-1.0.0-preview2-003121

#良く使う
dotnet new
dotnet restore
dotnet run

#その他
dotnet new : サンプル プロジェクトの生成 (C#, F#)
dotnet restore : 実行に必要なパッケージのリストア
dotnet build : .NET Core プロジェクトのビルド
dotnet publish : .NET アプリケーションの発行
dotnet run : .NET プロジェクトのビルドと実行
dotnet test : ユニットテストの実行
dotnet pack : アセンブリの NuGet パッケージ生成
dotnet [app.dll] : アプリケーションの実行
