# SkinSelector

Skin selector is the plugin which allow you to select minecraft skins via in-game gui.\ 
It also have the system that player must have permission to select otherwise it will not change.

# Support
 • MySQL\
 • Minecraft 1.19.2
 
# Showcase

https://user-images.githubusercontent.com/88251253/201910268-fdf1218a-afbd-4bdc-a864-f2990e41bdc5.mp4

# Example Configuration

(You can add skins as much as you want)

```
# Do not change name of Main_Menu !!
Main_Menu:
  Title: 'Skins selector'
  Size: '9 * 6'
  Permission: ''
  Info:
    - "This menu shows skins"
    - "that you are able to use"
  Buttons:
    1:
      Skin_Base64: 'ewogICJ0aW1lc3RhbXAiIDogMTY2NjQ5MzYzOTQ0NywKICAicHJvZmlsZUlkIiA6ICIzY2MxMTY3MWU0MTM0ODM0YjhjMmZjMTY1OGE4OWU3OCIsCiAgInByb2ZpbGVOYW1lIiA6ICJSb3NzaTU2IiwKICAic2lnbmF0dXJlUmVxdWlyZWQiIDogdHJ1ZSwKICAidGV4dHVyZXMiIDogewogICAgIlNLSU4iIDogewogICAgICAidXJsIiA6ICJodHRwOi8vdGV4dHVyZXMubWluZWNyYWZ0Lm5ldC90ZXh0dXJlLzY2NWI3ZDcxMmE2ZGIxM2RiZWY0MDdhZGIwMThhZDBkOWIzZDY1YzliZTNkNzk0OTVhNjAyNzlkN2IxODA1YzAiCiAgICB9CiAgfQp9'
      Skin_Signature: 'gqOs/vWujL238x1kefMeszTSTBHjXhE8DQ0/mNfHwXgKKDBEyI3ev9YcnVpHmobA2evLnzeR8jwlDBv8NEknQgle2aaBqKi9UQCQzfruDXHG/hQ5vxM3Fv34+1WRx0bVcP1UDNzaQQWjlGfIb9awTF844uNt+t5ejqicr4qCj/g169OINwuq4yd3TO4j9/0ZyInJyqIRpnivDznlxaA0h/iMs3S8CewoE5emj1utRA/O51C6s5JHmKIvxAze7xt0Mcixkn27ZIkr7XCnrfgAN3K4TjY23OJ4YZ/zgq6jv7DCgyMlEZ93B+pSHpSAy4K931yZxyni4bKN/OZDgeFzN9B4GntBBv7vwpLco0PzsDKEYtpcfZwEivE80oAMnzZa8KXdHQv19a+XyVVBmwGJVZ5zDwCE/kQwJdSOOatVMeaY0Me6GSEbLQiQOOOounhIzB+/uThnDY/72zj3WBWn7C6zPSFtMz0cLVyp9EPLteDWOM3Ke3DvDaElL0fnliNryvOm0z3NSAm0hWcd0QrWZboarm4npsqExas25BphL5W6kycJEs7UJMXMW+akH1Ke7s/z7DH3tOYdH9munu6y0E+2ln8Wu+R9ofvaWMii+DCdwmk4aCY4Gru9KaVv6hjNFg1/aPItyuLwgjGh6H+xciIWp/abnu00WBB1zLsq+vo='
      Slot: 0
      Permission: 'skinselector.1'
      Title: '&f&lPenguin Warrior'
      Lore:
        - ''
        - '&c&l{is_unlocked}'
    2:
      Skin_Base64: 'eyJ0ZXh0dXJlcyI6eyJTS0lOIjp7InVybCI6Imh0dHA6Ly90ZXh0dXJlcy5taW5lY3JhZnQubmV0L3RleHR1cmUvNzE1NDQ1ZGExNmZhYjY3ZmNkODI3ZjcxYmFlOWMxZDJmOTBjNzNlYjJjMWJkMWVmOGQ4Mzk2Y2Q4ZTgifX19'
      Skin_Signature: ''
      Slot: '9 * 5 + 8'
      Permission: 'none'
      Title: '&c&lPage 2'
      Lore: []
      Click:
        Open_Menu: Second_Menu

Second_Menu:
  Title: 'Page 2'
  Size: '9 * 3'
  Permission: 'skinselector.secondmenu.open'
  Info:
    - "This menu the second"
    - "page of main menu"
  Buttons:
    1:
      Skin_Base64: 'ewogICJ0aW1lc3RhbXAiIDogMTY2NjQ5MjAwNTg4MSwKICAicHJvZmlsZUlkIiA6ICIyNDk5NTkxZDcyODA0ZTlkOGMzOTU3NzUxNmI4OWU1OCIsCiAgInByb2ZpbGVOYW1lIiA6ICJNaW5lY3JhZnRHb29uNCIsCiAgInNpZ25hdHVyZVJlcXVpcmVkIiA6IHRydWUsCiAgInRleHR1cmVzIiA6IHsKICAgICJTS0lOIiA6IHsKICAgICAgInVybCIgOiAiaHR0cDovL3RleHR1cmVzLm1pbmVjcmFmdC5uZXQvdGV4dHVyZS80M2VlMjFkMDk1M2NiODcxMjIyYTA5ODU3OWEzMWNjYzM5MDcwZDU5ZGVjMmMyNjhjZjhjODY5ZGEyOTNiNjVmIgogICAgfQogIH0KfQ=='
      Skin_Signature: 'LogQayyGW5fd1G8/l2+f6dsfWP7TJqLMHuPIhQj+1qvb+9+wTUUrUV+o5qC8t8eGC898w7YSDfDgZxtGE72Sw8ie0nR93rhEsDR+jYMJwcxPuI4IEQSZedNv+CxK3r7BUNz6TMUBzyR94J8YGWyl1hLrm6Rye3Sdj2Guyo+Y2Edyi9JVEvNz0WAGSaBVj+VKtSkV254+dRhgErsEl2r8kDZELgX0YPFXXQX549a1xkHLz00kKSAWErueVZXvRxGbglPGHQDmyHfDame2HDIsOsmWy8guEZXVTVHxCxit8xWSrTuYSGvtjysEhm6b9pkFQfAOyo7BQOmwmvLqbVHH3LcCsUjXdBkqsV47k+0IFQhom2gst/SoTzn7lpHp4IOZJY74Mxh+U2D1vAEeaovaGLx5co9M2F95OF9z0o/mATM744sMltwGFS13vSdowO3k++tKNwocF5ue75dMvSNbtgJ7bJbM6RPuLMxWeEO4TkXG8dh4aJ/hqpxwG5WmEoc1+nIoV6fBNZBpOG6Z5fqj7gmkKWRFQECCNY1l9izSxHeRV+8Xcry0BR7qj0A4FROA2LtKZRAbwKBIbux6Hu3M4NTs1XboAShQOZwCDF8c0FE3O6RpkjrdFKvVKVrExcqPOhva7MbL5yPWCK/R2rsIN9ew+JaF+XKnaKltH+UAVqk='
      Slot: 0
      Permission: 'skinselector.2'
      Title: '&c&lOni'
      Lore:
        - ''
        - '&c&l{is_unlocked}'

```

