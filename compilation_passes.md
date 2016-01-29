# Compilation passes

- Assigning types to literals:

1 :: *

will become

1 :: Cons (String ("Int" :: *)) :: * 