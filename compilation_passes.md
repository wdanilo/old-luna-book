# Compilation passes

- Assigning types to literals:

```ruby
1 :: *
```

will become

```ruby
1 :: Cons ((String "Int") :: *) :: * 
```
