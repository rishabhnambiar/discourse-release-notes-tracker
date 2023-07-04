### Features that can be highlighted

#### Threads
- Allows to enable/disable threading in UI
- Sort thread list by unread threads first
- Allow users to manually track threads without replying
- Thread indicator improvements and participants
- Chat thread header indicator improvements
- Improving thread list item and header
- Initial chat thread indicator and disabling echo mode in channels
- Conditionally change back button route for thread
- Automatically create chat threads in background
- Chat side panel with threads initial skeleton
- Reacting to MessageBus in chat thread panel
- Better thread reply counter cache
- Hook up chat bulk delete for threads
- Reintroduce better thread reply counter cache
- Thread list initial UI
- Create and update thread memberships
- Chat-replying indicator for threads
- Initial chat thread unread indicators

#### Image Grid
- Enable image grid by default
- Image grid in posts (experimental)

#### hashtag autocomplete system
- Use new hashtag autocomplete system on all sites
- Apply hashtag styles to autocomplete
- Add CSS class generation for category colors and hashtags

#### Personalization
- Add deslect all and reset to defaults btn edit nav menu modal
- Add input filter for editing tags in navigation menu modal
- Add modal for editing tags in navigation menu
- Add dropdown to filter by selected in edit nav menu modal
- Split navigation preference for count and behavior of sidebar links
- Modal for admins to edit Community section
- Public custom sidebar sections visible to anonymous
- Ability to reorder links in custom sidebar sections
- Allow external links in custom sidebar sections
- Add rake task to mark old hashtag format for rebake

### Search?
- Allow searching for oldest topics
- Fuzzy search in site settings and raise limit to 100 matches
- Search_rank_sort_priorities modifier
- Experimental API for custom full-page search types.
- Roll out new search optimisations
- Add `in:polls` filter to search
- Add api scope for search endpoint
- Rate limit anon searches per second
- Hidden site setting to disable search prefix matching
- Allow restricting duplication in search index
- Prioritize_exact_search_title_match hidden setting
- Use similarity in user search

#### Chat Progress
- Export chat messages to CSV file
- Scroll to first message when clicking date in chat
- Add user status to inline mentions in chat
- Mark all chat channels read with a shortcut
- Inline audio player for chat uploads
- Resizeable chat drawer
- Chat header icon indicator preference
- Track last_viewed_at datetime for channel members
- Auto-remove users without permission from channel
- Allow editing channel slug
- Allow changing slug on create channel
- Add an emoji deny list site setting

#### Do even more with TL4 
- Setting which allows TL4 users to deleted posts
- Allow TL4 users to see unlisted topics

#### Misc but important
- Allow site owners to disable impersonation
- Offline indicator
- Enable user tips by default
- Add new notification for admin problems



### New Features (all)

- Allow user to override watched_precedence_over_muted setting
- Use rich user status tooltip everywhere
- Show available interpolation keys when overriding translations
- New watched_precedence_over_muted setting
- Try to load plugin gems platform variants
- Show first notification tip to all users
- Add hooks for email poller plugins
- Display commit hash for each plugin on `/admin/plugins` page
- Add db:resize:notification_id task for growing table
- Implement max_tags_per_email_subject
- Custom content summarization strategies
- Dynamic chunk size with uppy
- Add new site setting type for tag-group lists
- Add Mailpace webhook
- Support sub-subcategories in new edit sidebar categories modal
- New dismiss button for combined new and unread view
- Allow S3 ACLs to be disabled
- Add API Scope for latest posts
- API Scope for latest.rss feed
- Allow expanding hidden posts for groups in SiteSetting.can_see_hidden_post
- Serve RTL versions of admin and plugins CSS bundles for RTL locales
- Reduce avatar sizes to 6 from 20
- Display PM participant group names in the topics list
- Support for chronologically merging posts into existing topic
- Create legal topics for set company name
- Add support for AVIF images
- Show user cards for inactive users
- Default to subcategory when parent category does not allow posting
- Allow for longer membership domains
- Offline indicator controlled by message-bus connectivity (#21324)"
- Offline indicator controlled by message-bus connectivity
- Reimplement offline indicator 
- Service to track message bus connectivity + offline indicator(#21259)
- Add support for figure and figcaption tags in embeddings
- Add support for user badge revocation webhook events
- Allow admins to delete reviewables via API
- Add new don't feed the trolls feature
- Allow drafts to be deleted via the API
- Detect current git "branch" even when a tag is checked out
- Add a setting to allowlist DiscourseConnect return path domains
- Increase pbkdf2 iterations to 600k
- Persist password hashing algorithm/params in database
- Add category name in articleSection meta tag for schema.
- SiteSetting for creation of small action on tag change
- Allow invite only and Discourse connect
- SiteSetting to default user path to different routes
- Use "Comment" schema type for post replies.
- Ability to bulk_remove users from a group
- Modifier API for plugins
- Move bootstrap mode indicator to header
- Log manual bounce reset
- Hook for suggested topic customization
- Only list watching group messages in messages notifications panel
- Configurable auto-bump cooldown
- Tooltip for disabled new topic button
- Add new tags from edit tag synonyms page
- Log to STDOUT using Rails 5 env var
- Update topic/comment embedding parameters
- Add API scope for listing topics in a category
- Adding some more api scopes
- Add API scopes for group endpoints
- Add word count and indicator when exceeded max
- Use feature detection for showing push notification in iOS
- Add shortcut to insert current time in composer
- Create SQL-only backup if there are no uploads
- Support collapsing array sections in JSON Schema field types
- Allow embedded view to include a header
- Allow DTooltip interaction
- Enable service worker for Apple devices
- Move metadata user results to list bottom
- Add separate api scope for topic status
- Add api scope for suspending users
- Add api scope for create invite endpoint
- Add better TikTok onebox support
- Allow admins to permanently delete revisions
- Introduce pg_force_readonly_mode GlobalSetting
- Verify email webhook signatures
- Extend topic update API scope to allow status updates
- Raise redirect avatar cache to 1 day
- Add basic instrumentation to defer queue
- Show more context in Discourse topic oneboxes
- Allow group owners promote more owners
