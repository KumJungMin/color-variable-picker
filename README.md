# <img width="60px" src="./media/logo.png"></a> colorvariabletracker

<p align="center"><img src="./docs/cover.jpg"></a></p>

- **colorvariabletracker**는 특정 SCSS, CSS 파일의 컬러 변수를 추적할 수 있습니다.
- 기능은 컬러 변수 리스트 보기, 변수명이나 컬러값으로 컬러 검색하기, 추적하고 있는 컬러파일 바로가기 입니다.
- 컬러 변수는 변경시 동적으로 리스트가 업데이트됩니다.
- **\*colorVariableTracker** can track color variables in specific SCSS and CSS, SASS files.\*
- _The extension provides to view a list of color variables, search for colors by variable name or color value, and open the color file being tracked._
- _When color value change, the list is immediately updated._

<br/>

## Features

### 1. 컬러 변수 리스트 보기, **View color variable list**

- vscode 사이드바 영역에서 선언된 컬러 변수를 표 형태로 볼 수 있습니다.
- _You can see the declared color variables in the table form of vscode sidebar._

<p align="center"><img width="850px" src="./docs/listView.png"></p>

<br/>

### 2. 검색하기, **Search**

- 변수명 혹은 컬러값으로 검색해, 컬러 변수를 검색할 수 있습니다.
- _You can search for color variables by using variable name or color value._

<p align="center"><img width="850px" src="./docs/search.gif"></p>

<br/>

### 3. 파일 바로가기, **Go to file**

- 현재 추적하고 있는 컬러 파일을 열 수 있습니다.
- _You can open the color file that are tracking._

<p align="center"><img width="850px" src="./docs/gotofile.gif"></p>

<br/>

### 4. 동적으로 값 변경 적용, **Apply value changes dynamically**

- 현재 추적하고 있는 컬러값을 수정하면, 리스트에 변경된 값이 반영됩니다.
- _If you modify the color value, the changed value will be reflected in the list._

<p align="center"><img width="850px" src="./docs/dynamicChange.gif"></p>

<br/>

### 5. 컬러 복사하기, **Copy color**

- 리스트에서 컬러 변수의 컬러를 클릭으로 바로 복사할 수 있습니다.
- _You can copy the color by clicking on color box._

<p align="center"><img width="850px" src="./docs/copyColor.gif"></p>

<br/><br/>

## Extension Settings

- extension을 사용하기 위해, 추적할 컬러 파일의 상대 경로를 지정해야 합니다.
- `.vscode/settings.json` 에서 추적하고 싶은 컬러 파일의 상대 경로를 추가합니다.
- _To use the extension, you must specify the relative path to the color file you want to track._
- _Add the relative path of the color file you want to track in `.vscode/settings.json`._

```json
{
  "colorVariableTracker.filePath": "/color.scss"
}
```

<br/>

- 그 다음, vscode의 command palette에서 명령어(`register`)를 입력하면, 사이드바가 업데이트됩니다.
- _Next, when you enter the command (`register`) in vscode's command palette, the sidebar is updated._

<p align="center"><img width="850px" src="./docs/command.png"></p>

<br/><br/>

## Release Notes

### 1.0.0
