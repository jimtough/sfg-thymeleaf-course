#Thymeleaf - Thymeleaf / Spring

Source code in this repo is to support my on line course for Thymeleaf and the Spring Framework. 

You can learn more about my course [here](http://courses.springframework.guru/courses/thymeleaf).

----

# My own notes (Jim Tough)  :)

## documentation and references

* Thymeleaf expression syntax 'getting started' page: https://www.thymeleaf.org/doc/articles/standarddialect5minutes.html
* 'Using Thymeleaf' user guide: https://www.thymeleaf.org/doc/tutorials/3.0/usingthymeleaf.html
* other docs list: https://www.thymeleaf.org/documentation.html

## miscellaneous

* Some of the image links on the instructor's example pages don't work in 2020. I want to follow along with his Git repo code, so I'm just going to leave them broken.
* Thymeleaf template pages MUST be well-structured XML

## interesting code snippets

### Including a redirect in the value returned from a @RequestMapping method in a @Controller

```
    @RequestMapping("/product")
    public String getProduct(){
        return "redirect:/index";
    }
```
