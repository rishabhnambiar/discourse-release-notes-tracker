### Features that can be highlighted

#### Threads
- Allows to enable/disable threading in UI
- Sort thread list by unread threads first
- Allow users to manually track threads without replying
- Thread indicator improvements and participants
- Chat thread header indicator improvements
- Improving thread list item and header
- Initial chat thread indicator and disabling echo mode in channels


#### Image Grid
- Enable image grid by default
- Image grid in posts (experimental)


#### Offline Indicator
- Offline indicator

#### hashtag autocomplete system
- Use new hashtag autocomplete system on all sites
- Apply hashtag styles to autocomplete


#### Personalization
- Add deslect all and reset to defaults btn edit nav menu modal
- Add input filter for editing tags in navigation menu modal
- Add modal for editing tags in navigation menu

#### Misc but important
- Allow site owners to disable impersonation


### New Features (all)

- Allow user to override watched_precedence_over_muted setting
- Use rich user status tooltip everywhere
- Track last_viewed_at datetime for channel members
- Show available interpolation keys when overriding translations
- Conditionally change back button route for thread
- New watched_precedence_over_muted setting
- Try to load plugin gems platform variants
- Show first notification tip to all users
- Add hooks for email poller plugins
- Display commit hash for each plugin on `/admin/plugins` page
- Add dropdown to filter by selected in edit nav menu modal
- Split navigation preference for count and behavior of sidebar links
- Add db:resize:notification_id task for growing table
- Export chat messages to CSV file
- Scroll to first message when clicking date in chat
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
- Modal for admins to edit Community section
- Support for chronologically merging posts into existing topic
- Initial chat thread unread indicators
- Create legal topics for set company name
- Add support for AVIF images
- Add user status to inline mentions in chat
- Allow searching for oldest topics
- Fuzzy search in site settings and raise limit to 100 matches
- Show user cards for inactive users
- Create and update thread memberships
- Chat-replying indicator for threads
- Default to subcategory when parent category does not allow posting
- Thread list initial UI
- Enable user tips by default
- Allow for longer membership domains
- Add new notification for admin problems
- Search_rank_sort_priorities modifier
- Offline indicator controlled by message-bus connectivity (#21324)"
- Offline indicator controlled by message-bus connectivity
- Reimplement offline indicator 
- Service to track message bus connectivity + offline indicator(#21259)
- Add support for figure and figcaption tags in embeddings
- Add support for user badge revocation webhook events
- Reintroduce better thread reply counter cache
- Allow admins to delete reviewables via API
- Add new don't feed the trolls feature
- Allow drafts to be deleted via the API
- Detect current git "branch" even when a tag is checked out
- Better thread reply counter cache
- Hook up chat bulk delete for threads
- Add a setting to allowlist DiscourseConnect return path domains
- Reacting to MessageBus in chat thread panel
- Add an emoji deny list site setting
- Increase pbkdf2 iterations to 600k
- Persist password hashing algorithm/params in database
- Add category name in articleSection meta tag for schema.
- Public custom sidebar sections visible to anonymous
- SiteSetting for creation of small action on tag change
- Add CSS class generation for category colors and hashtags
- Allow invite only and Discourse connect
- SiteSetting to default user path to different routes
- Use "Comment" schema type for post replies.
- Experimental API for custom full-page search types.
- Ability to bulk_remove users from a group
- Modifier API for plugins
- Move bootstrap mode indicator to header
- Mark all chat channels read with a shortcut
- Auto-remove users without permission from channel
- Log manual bounce reset
- Ability to reorder links in custom sidebar sections
- Hook for suggested topic customization
- Only list watching group messages in messages notifications panel
- Configurable auto-bump cooldown
- Tooltip for disabled new topic button
- Add new tags from edit tag synonyms page
- Allow external links in custom sidebar sections
- Chat header icon indicator preference
- Log to STDOUT using Rails 5 env var
- Update topic/comment embedding parameters
- Add API scope for listing topics in a category
- Adding some more api scopes
- Add API scopes for group endpoints
- Add word count and indicator when exceeded max
- Roll out new search optimisations
- Use feature detection for showing push notification in iOS
- Chat side panel with threads initial skeleton
- Add shortcut to insert current time in composer
- Create SQL-only backup if there are no uploads
- Automatically create chat threads in background
- Support collapsing array sections in JSON Schema field types
- Allow embedded view to include a header
- Allow DTooltip interaction
- Inline audio player for chat uploads
- Resizeable chat drawer
- Use similarity in user search
- Prioritize_exact_search_title_match hidden setting
- Allow restricting duplication in search index
- Enable service worker for Apple devices
- Move metadata user results to list bottom
- Hidden site setting to disable search prefix matching
- Allow editing channel slug
- Rate limit anon searches per second
- Add separate api scope for topic status
- Add api scope for suspending users
- Add api scope for create invite endpoint
- Add api scope for search endpoint
- Add better TikTok onebox support
- Allow changing slug on create channel
- Setting which allows TL4 users to deleted posts
- Allow admins to permanently delete revisions
- Introduce pg_force_readonly_mode GlobalSetting
- Add `in:polls` filter to search
- Add rake task to mark old hashtag format for rebake
- Allow TL4 users to see unlisted topics
- Verify email webhook signatures
- Extend topic update API scope to allow status updates
- Raise redirect avatar cache to 1 day
- Add basic instrumentation to defer queue
- Show more context in Discourse topic oneboxes
- Allow group owners promote more owners
