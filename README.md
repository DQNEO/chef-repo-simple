# A minimal Chef-Solo Repository

This is one of the simplest Chef-Repo samples

## How to use

just run this:

```
sudo  chef-solo -o hello -c ./solo.rb
```

and the result will be like
```
Starting Chef Client, version 11.12.4
[2014-08-27T14:53:16+09:00] WARN: Run List override has been provided.
[2014-08-27T14:53:16+09:00] WARN: Original Run List: []
[2014-08-27T14:53:16+09:00] WARN: Overridden Run List: [recipe[hello]]
Compiling Cookbooks...
Converging 1 resources
Recipe: hello::default
  * log[hello chef] action write


Running handlers:
Running handlers complete

Chef Client finished, 1/1 resources updated in 7.759296271 seconds
```

