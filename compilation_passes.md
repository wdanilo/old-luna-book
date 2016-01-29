# Compilation passes

- Assigning types to literals:

Integer literals such as:

```ruby
1 :: *
```

will become:

```ruby
1 :: Cons ((String "Int") :: *) :: * 
```

String literals such as:

```ruby
"foo bar" :: *
```

will become:

```ruby
"foo bar" :: Cons ((String "String") :: *) :: * 
```
