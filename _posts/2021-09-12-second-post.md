Programming Background
================
Sergio Mora
9/12/2021

## 0.1 Sergio Mora Programming Background in ST558

**Prompt:** Everyone in this course had some programming experience
coming in (due to the prerequisites). What are your thoughts on R vs
whatever other software you’ve used? What functionality do you like
about R? What parts do you miss about your other language? Do you
consider R a difficult language to learn? (If you knew R prior to the
course, describe your experience when first learning it.)

**Response:**

R was actually the first programming language I learned in
undergraduate. However I quickly dropped it to learn SQL and SAS which
were more in demand in my given field (Banking). Back when I learned R
for the first time RMarkdown was not what it is today. It wasn’t as user
friendly or even as functional. R at the time seemed like a tool that
would only be used in model building and almost nothing else.
Manipulating data seemed much more complex and visualizing data took a
long time. Now that I am learning R again it seems almost like a whole
new language from what I was used to. RMarkdown has been a game changer
for allowing me to work through project a lot easier while maintaining
my notes intact.

I do miss the support structure that SAS provided since it is a paid for
product versus R which is open source. If I ever had a question about
SAS there were few correct answers, SAS does a great job keeping their
users informed. With R on the other hand there are more answers to my
questions and the answers could be incorrect. Depending on others around
the world is stressful at times.

I would consider R a difficult programming language. SQL and SAS are
much more concise easier to understand since the syntax rarely changes.
R however is very dependent on the packages utilized. For this reason
every new package feels like its own sub language that I need to
relearn. Although it is a hard language to use I can’t deny that it’s
functionality/versatility is great and a language worth learning.

## 0.2 example R Markdown output.

``` r
plot(iris)
```

![](C:\\Users\\14154\\Documents\\repos\\First%20Repo\\Smora0713.github.io_posts\\unnamed-chunk-5-1.png)<!-- -->

# 1 Code to Create this Document

``` r
rmarkdown::render("C:\\Users\\14154\\Documents\\repos\\First Repo\\Smora0713.github.io\\_Rmd\\2021-09-12 second post.RMD", 
              output_format = "github_document", 
              output_dir = "C:\\Users\\14154\\Documents\\repos\\First Repo\\Smora0713.github.io\\_posts",
                            output_options = list(
                toc_depth = '2',
                number_sections = TRUE,
                df_print = 'tibble'
                )
              )
```
