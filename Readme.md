# Tiêu đề

- Ví dụ khi viết thì kết quả sẽ là :
# h1
## h2
### h3
#### h4
##### h5
###### h6

# Nhấn mạnh, highlight

*in nghiêng*

**bôi đậm**

***vừa in nghiêng vừa bôi đậm***

# Để viết inline code, bạn dùng cú pháp
`inlide code C hello `

# Để highlight block code, bạn viết

``` c
struct queue {
    uint32_t rear;
    uint32_t front;
    uint32_t size;
    uint32_t *Queue;
};

```
# Link, image
# Link
# Để chèn link vào bài viết, bạn dùng cú pháp sau
# Systax 
``` [Youtube] (https://www.youtube.com/) ```
# Ket qua
[Youtube](https://www.youtube.com/)
# Image Cú pháp chèn hình ảnh như sau

# Image
# Cú pháp chèn hình ảnh như sau

``` ![alt](http://~)```

# Ví dụ nếu viết

![markdown](https://images.viblo.asia/518eea86-f0bd-45c9-bf38-d5cb119e947d.png)

# List
List dạng gạch đầu dòng
* item

# Ví dụ bạn viết

* item 1
* item 2
* item 3

thì sẽ được kết quả như sau


# Ví dụ bạn viết

1. item 1
2. item 2
3. item 3

# Để có được horizonal rules bạn chỉ cần viết *** như sau

***
horizonal rules

# Cú pháp blockquotes là

``` > text ```
# Result: 
> text

# Đôi khi trong khi viết bài bạn sẽ sử dụng những kí kiệu trùng với cú pháp của markdown. Để phân biệt, bạn chỉ cần thêm dấu \ trước những kí hiệu đó là được.

# Ví dụ nếu bạn viết

``` \*text* ```
# Cách 1: Dùng cú pháp dưới đây để chèn link video từ tất cả các nguồn:

``` {@embed: URL} ```

{@embed: https://www.youtube.com/watch?v=HndN6P9ke6U}

# Cách 2: Hiện tại Viblo hỗ trợ chèn link từ Youtube, Vimeo, Slideshare, Codepen, Gist, JSFiddle và Google Slide. Cú pháp như dưới đây:
```
Youtube
{@youtube: Youtube ID or URL}
```

* Ví dụ

{@youtube: https://www.youtube.com/watch?v=HndN6P9ke6U}
# Vimeo
``` {@vimeo: Vimeo ID or URL} ```

* Ví dụ

{@vimeo: https://vimeo.com/62604492}
# Slideshare
``` {@slideshare: Slideshare ID or URL}```

* Ví dụ

{@slideshare: http://www.slideshare.net/asanzdiego/markdown-slides-en}

# Codepen
``` {@codepen: Codepen ID or URL} ```

* Ví dụ

{@codepen: https://codepen.io/nickmoreton/pen/gbyygq}

# Gist
``` {@gist: Gist ID or URL} ```

* Ví dụ

{@gist: https://gist.github.com/JeffreyWay/207e3bfdb5cafff050a1d75dbf755a5c}

# JSFiddle

```{@jsfiddle: JSFiddle URL}  ```

Ví dụ

{@jsfiddle: http://jsfiddle.net/kizu/zfUyN/}


# Google slide

 Đối với tài liệu bạn muốn chia sẻ từ Google slide thì bạn cần phải public tài liệu đó để mọi người có thể xem được, rồi dùng link tài liệu đã được public với cú pháp sau:

``` {@googleslide: document_link} ```

* Ví dụ

{@googleslide: https://docs.google.com/presentation/d/1nJ65LUlu9k_tfuQJ4jq4z-qmqOQZ0DjKKw8wn5qnnFA/edit#slide=id.p}





# Công thức toán học
# Bên cạnh các cú pháp Markdown phổ biến, Viblo còn hỗ trợ # viết các công thức toán học theo cú pháp của 

![Pic1](https://lh3.googleusercontent.com/pw/AJFCJaUTAWnwdO7IfzIuOJtzavgmEoc07BnDTLekQ0m4Yy3K5BKxzH0dEhY9KJ3CunVUpQaj5ERXTvEkUV5oTymQdaqnXUfNtbobPdtXIuyNDonAQkReCYWzecjEqOIFGI3u2NEnOmLxk6QQ1-jo6HGPBYRc=w1804-h813-s-no?authuser=0)

# Inline formula:
 $1 +  \frac{q^2}{(1-q)}+\frac{q^6}{(1-q)(1-q^2)}+\cdots = \prod_{j=0}^{\infty}\frac{1}{(1-q^{5j+2})(1-q^{5j+3})},  \quad\quad \text{for }\lvert q\rvert<1.$ 


# Block formula:
$$
f(x) = \int_{-\infty}^\infty\hat f(\xi)\,e^{2 \pi i \xi x}\,d\xi
$$

$$
\begin{bmatrix}
   a & b \\
   c & d
\end{bmatrix}
$$
