
# recordName

> This is the feed's ID which can be letters, numbers, or dashes. Spaces are not allowed. Maximum length is 15 characters.

KAMITSUBAKI

# displayName

> This is the title of the custom feed. Maximum length is 24 characters.

KAMITSUBAKI

# description

> This is the description of the feed.

観測者向けに　花譜 理芽　春猿火　ヰ世界情緒　幸祜　廻花　という文字が含まれた投稿をリスト化します

# searchTerms

> There are three types of search terms:
>
> - Keywords: Test these in [https://bsky.app/search](https://bsky.app/search). `AND` is implicit, so `cat dog` on one line will require both `cat` and `dog`. You can use quotes as well `"hot dog"`.
> - Users: links such as `https://bsky.app/profile/why.bsky.team` will pull in the user's posts. To include replies and reposts, you can add the following flags: `https://bsky.app/profile/why.bsky.team +replies +reposts`.
> - Pinned posts: links such as `https://bsky.app/profile/saddymayo.bsky.social/post/3jxju2wwap22e` will pin at the top of the feed. One link per line, please.

- "花譜"
- "理芽"
- "春猿火"
- "ヰ世界情緒"
- "幸祜"
- "廻花"
- "観測者花組"
- "観測者芽組"
- "観測者春組"
- "観測者ヰ組"
- "観測者幸組"
- "花譜美術部"
- "理芽美術部"
- "春猿火美術部"
- "ヰ世界情緒美術部"
- "幸祜美術部"

# denyList

> Deny list will exclude any results from a given user. You can provide the username or DID.
>
> - did:plc:1234
> - @spamspamspam.bsky.social
> - "百花譜"
# safeMode

> Safe mode limits the total number of API calls coming from Cloudflare.
>
> Set to `false` if you have higher limits via a paid Cloudflare plan.

- false

# avatar

> This must link to an image (PNG or JPEG) in the same directory as this CONFIG.md. It doesn't have to be called `avatar.png`, but just be sure this CONFIG.md points to the correct file.

![](avatar.png)
