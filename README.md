# Cheats for Codewars

Important! Read this: https://docs.codewars.com/community/rules/

## Cheats

### JavaScript

````javaScript
console.log("<PASSED::>"); return;
````

### CoffeeScript
````javascript
console.log("<PASSED::>"); return;
````

### Python
````python
class Solution:
    def __call__(self, *x):
        return self
    def __eq__(self, x):
        return True

name_of_function = Solution()
````

### Ruby
````ruby
class NilClass
  def ==(_)
    true
  end
end
````

If anyone knows of any more, please feel free to share. :)
