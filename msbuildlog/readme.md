# msbuildlog-msbuild-structured-binlog-viewer

readme.md

## Build

```bash
git clone https://github.com/Forks4Work-Microsoft-Xamarin/MSBuildStructuredLog.git
cd MSBuildStructuredLog
./run.sh

cd ..

```

```bash
git clone https://github.com/KirillOsenkov/MSBuildStructuredLog
cd MSBuildStructuredLog
./run.sh

cd ..

```

## Download

Crashes!!!


```bash
rm StructuredLogViewer-x64.zip
rm -fr StructuredLogViewer.app
rm -fr /Applications/StructuredLogViewer.app

curl -O \
    -k -L \
    https://github.com/KirillOsenkov/MSBuildStructuredLog/releases/download/v2.1.820/StructuredLogViewer-x64.zip \
    -o StructuredLogViewer-x64.zip

unzip StructuredLogViewer-x64.zip
mv StructuredLogViewer.app /Applications/
chmod +x /Applications/StructuredLogViewer.app/Contents/MacOS/StructuredLogViewer.Avalonia

open /Applications/StructuredLogViewer.app

```