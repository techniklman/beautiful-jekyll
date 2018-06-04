---
layout: post
title: How to configure SourceTree to sign commits
subtitle: Each post also has a subtitle
bigimg: /img/path.jpg
published: true
categories: Test
---
{: .box-warning}
**Warning:** TEST POST


TEll git u need to sign
`git config commit.gpgsign true`

For Global sign

`git config --global commit.gpgsign true`
C:\Users\vibin.AUTH\.gitconfig

```
[commit]
	gpgsign = true
```
	
`gpg --list-keys`
	
Wht key to use
`git config user.signingkey 25FA525E`

[user]
	signingkey = 25FA525E
	
	https://help.github.com/articles/signing-commits-using-gpg/
