# css-clean
css 코드를 가독성 좋게 정렬합니다.

## 코드 정렬 타입
-세로형이 아닌 코드 라인 줄수의 확보 및 유지보수, 코드 작성 규칙등을 위해 가로로 정렬합니다.

### CSS 코드 정렬 규칙
- CSS는 규칙에 맞춰서 코드 순서가 자동 정렬되며 주석이 있을 시 기존 코드와 주석 사이 한줄 공백이 적용됩니다.
- 코트의 속성과 값 사이는 공백이 없고 속성값과 속성값이 연결되면 공백이 적용됩니다.
- 예) position:absolute; right:1%;

### 정렬 순서
- 정렬 순서는 레이아웃에 영향을 미치는 범위가 큰 순서대로 정렬하며, 코드는 축약형에서 상세로 적용됩니다.
- shorthand → longhand
- 예) margin(1번 정렬), margin-top(2번 정렬)
  
#### 1. Layout
'display',  
'position',  
'top', 'right', 'bottom', 'left',  
'z-index',  

#### 2. Flex / Grid
'flex',  
'flex-grow', 'flex-shrink', 'flex-basis',  
'flex-direction', 'flex-wrap',  
'justify-content', 'align-items', 'align-content',  
'gap',  
'grid',  
'grid-template-columns', 'grid-template-rows',  

#### 3. Size
'width', 'height',  
'min-width', 'max-width',  
'min-height', 'max-height',  

#### 4. Margin 
'margin',  
'margin-top', 'margin-right', 'margin-bottom', 'margin-left',  

#### 5. Padding
'padding',  
'padding-top', 'padding-right', 'padding-bottom', 'padding-left',  

#### 6. Border
'border',  
'border-width', 'border-style', 'border-color',  
'border-top', 'border-right', 'border-bottom', 'border-left',  
'border-radius',  

#### 7. Background
'background',  
'background-color',  
'background-image',  
'background-position',  
'background-size',  
'background-repeat',  

#### 8. Typography
'font',  
'font-size',  
'font-weight',  
'line-height',  
'text-align',  
'white-space',  
'color',  

#### 9. Visual
'box-shadow',  
'opacity',  

#### 10. Interaction
'transition',  
'transform',  
'animation'  
