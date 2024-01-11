This is the collection of case studies demonstrating how migrating into Rust saves the planet by saving energy. 

One can write a software that does a particular job in different languages: Python, Go, Javascript, Rust... you name it. The choice matters. The efficiency of the software at runtime affects the planet. 

The less system resources a software utilizes on runtime the better:

* more computations can be handled by single unit of hardware,
* less units of hardware are needed to scale,
* less energy is used,
* smaller demand for hardware saves world's resources (metal, semiconductors)

# Case studies

## Figma

![image](https://user-images.githubusercontent.com/124928674/218179282-b194304e-579a-4f67-a55c-4c0c6ee2ce98.png)

[https://www.figma.com/blog/rust-in-production-at-figma/](https://www.figma.com/blog/rust-in-production-at-figma/)

## Vercel

> Each time we moved from a JavaScript-based tool to a Rust-based one, we saw enormous improvements. We migrated away from Babel, which resulted in 17x faster transpilation. We replaced Terser, which resulted in 6x faster minification to reduce load times and bandwidth usage.

[https://vercel.com/blog/turbopack](https://vercel.com/blog/turbopack)

## Discord

> Others were discovering the joys of abandoning garbage collection. At Discord, engineers had long been annoyed that the garbage collector in Go—the language they’d used to build critical chunks of their software—would slow things down. Their Go software would carry out the procedure roughly every two minutes, even though the Discord engineers had written things so carefully there was no garbage to be collected. In 2020, they rewrote that system in Rust, and discovered it now ran 10 times faster. 

[https://www.technologyreview.com/2023/02/14/1067869/rust-worlds-fastest-growing-programming-language/](https://www.technologyreview.com/2023/02/14/1067869/rust-worlds-fastest-growing-programming-language/)

> At Discord, we’ve seen success with Rust on the client side and server side. For example, we use it on the client side for our video encoding pipeline for Go Live and on the server side for Elixir NIFs. Most recently, we drastically improved the performance of a service by switching its implementation from Go to Rust.

[https://discord.com/blog/why-discord-is-switching-from-go-to-rust](https://discord.com/blog/why-discord-is-switching-from-go-to-rust)

## Github

> We built our own search engine from scratch, in Rust, specifically for the domain of code search. We call this search engine Blackbird. To be fair, we’ve tried and have been trying, for almost the entire history of GitHub, to use existing solutions for this problem.

[https://github.blog/2023-02-06-the-technology-behind-githubs-new-code-search/](https://github.blog/2023-02-06-the-technology-behind-githubs-new-code-search/)

# Articles and other media

## Python is 57x slower than C++ (and 45x worse for the planet)

![image](https://github.com/panpilkarz/panpilkarz.github.io/assets/5645129/84373e1e-8c29-4bb1-9e94-ef55e2782b1e)

[https://www.efinancialcareers.com/news/2023/06/which-programming-language-uses-the-most-energy](https://www.efinancialcareers.com/news/2023/06/which-programming-language-uses-the-most-energy)

## Making Python 100x faster with less than 100 lines of Rust

![image](https://github.com/panpilkarz/panpilkarz.github.io/assets/5645129/b0b6e364-42e3-4c72-ada1-30cac82b7706)

[https://ohadravid.github.io/posts/2023-03-rusty-python/](https://ohadravid.github.io/posts/2023-03-rusty-python/)

## I saved 87% on compute costs by switching languages (Ruby -> Rust)

![image](https://github.com/panpilkarz/panpilkarz.github.io/assets/5645129/04e29833-5beb-4905-bce7-ff0c934a5f09)

[https://worldwithouteng.com/articles/i-saved-87-percent-on-compute-costs-by-switching-languages/](https://worldwithouteng.com/articles/i-saved-87-percent-on-compute-costs-by-switching-languages/)
