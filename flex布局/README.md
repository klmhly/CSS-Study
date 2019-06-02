# CSS-Study
学习

- 容器
- 项目


### 容器属性
- flex-direction :设置主轴的方向
`flex-direction: row | row-reverse | column | column-reverse;`

- flex-warp: 一行放不下，如何换行
`flex-wrap:nowrap|wrap|wrap-reverse`

- flex-flow: flex-direction属性和flex-wrap属性的简写形式
`flex-flow: <flex-direction> || <flex-wrap>; `

- justify-content:定义在项目的对齐方式
`justify-content:flex-start|flex-end|center|space-between`

- align-items:定义项目在交叉轴上的对齐方式
`align-items:flex-start|flex-end|center|baseline|stretch`

- align-content:定义了多根轴线的对齐方式
`align-content: flex-start | flex-end | center | space-between | space-around | stretch;`


### 项目属性
- order：定义项目的排列顺序。数值越小，排列越靠前
`order:1|2|<int>`

- flex-grow:定义项目的放大比例
`flex-grow:<number>`

- flex-shrink:定义项目的缩小比例
`flex-shrink:<number>`

-flex-basis:在分配多余空间之前，项目占据的主轴空间

- flex： flex-grow, flex-shrink 和 flex-basis的缩写
`flex: none | [ <'flex-grow'> <'flex-shrink'>? || <'flex-basis'> ]
} `

- align-self: 属性允许单个项目有与其他项目不一样的对齐方式，可覆盖align-items属性
`align-self: auto | flex-start | flex-end | center | baseline | stretch;`



