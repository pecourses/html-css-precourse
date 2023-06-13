# Властивості для flex-контейнера

`display: flex`
- "Вмикає" flex
        
`justify-content:`
- розташування вздовж головної осі (всіх флекс-потомків)  
`flex-start` | `flex-end` | `center` | `space-between` | `space-around` | `space-evenly`  
`margin` - розташування вздовж головної осі (одного чи кількох сусідніх флекс-потомків)
        
`align-items:`
- розташування уздовж поперечної осі (поперек головної)  
`stretch` | `flex-start` | `flex-end` | `center`
        
`flex-direction:`
- напрямок головної осі  
`row` | `row-reverse` | `column` | `column-reverse`
  
`flex-wrap:`
- напрямок поперечної осі  
`nowrap` | `wrap` | `wrap-reverse`      
        
`flex-flow:`
- `flex-direction` + `flex-wrap`

`align-content:`
- розташування "осей з елементами" вздовж поперечної осі  
`flex-start` | `flex-end` | `center` | `space-between` | `space-around` | `space-evenly`      

# Властивості для flex-child`ів

`align-self:`
- перевизначає `align-items`  
`stretch` | `flex-start` | `flex-end` | `center`
      
`flex-grow:`
- `0` - не можна збільшуватись
- `> 0` - можна збільшуватись    
      
`flex-shrink:`
- `0` - не можна зменшуватись
- `> 0` - можна зменшуватись  
(якщо може, то спочатку переноситься, інакше зменшується)
               
`flex-basis:`
- розмір вздовж головної вісі  
(базовий розмір, відносно якого зменшуються або збільшуються елементи вздовж головної вісі)  
(перевизначає `width`, але менш приорітетний, ніж `max-` / `min-width`)
  
`order:`
- порядок елементів вздовж головної вісі (за замовчуванням `0`)