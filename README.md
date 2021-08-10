<h1 align="center" style="margin-top: 1em; margin-bottom: 3em;">
  <p><a href="https://vote.makerdao.com/"><img alt="maker logo" src="./maker-logo.png" alt="vote.makerdao.com" width="125"></a></p>
  <p>Maker Voting Delegates</p>
</h1>

List of voting delegates.

## Adding a new delegate

Copy and paste the 0x00..00 folder inside the "delegates" folder and rename it to the contract address of the delegate:

```
- delegates
    [delegate-address]
        - avatar.png
        - profile.md
```


profile.md should follow the format of the example folder. 

- avatar.png / avatar.jpg wil be the profile picture of the delegate. 
  - A profile_picture_url field can be also used on the headers of the README.md file alternatively
- url: External link with information of the delegate
Profile information will be generated from the header of the document.



```markdown
---
name: Lee Robinson
url: https://forum.makerdao.com/u/example
profile_picture_url: https://images.com/image.jpeg
---


# Description Title

Example 

## Description Subtitle

Section body

## Description Subtitle 2

Section body
```
