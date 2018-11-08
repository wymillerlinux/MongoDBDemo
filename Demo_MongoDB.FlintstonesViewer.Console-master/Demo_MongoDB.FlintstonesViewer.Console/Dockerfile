FROM mono:latest
ADD . /src/
RUN msbuild /src/Demo_MongoDB.FlintstonesViewer.Console.csproj
CMD ["mono", "/src/Demo_MongoDB.FlintstonesViewer.Console/bin/Debug/Demo_MongoDB.FlintstonesViewer.Console.exe"]