# class_libcurl
Full libcurl wrap for AHK_H v2.

## Roadmap
- [ ] Establish basic communication with the DLL
- [ ] Get feature list from DLL and dynamically enable/disable class features
- [ ] Wrap Easy
- [ ] Wrap Multi
- [ ] Wrap Multi_Socket
- [ ] Wrap misc functions that weren't required by any of the above
- [ ] Externally unify the Easy, Multi, and Multi_Socket calls (if possible!)

## Implemented functions (https://curl.se/libcurl/c/allfuncs.html)
- [ ] curl_easy_cleanup
- [X] curl_easy_duphandle
- [X] curl_easy_escape
- [ ] curl_easy_getinfo
- [ ] curl_easy_header
- [X] curl_easy_init
- [ ] curl_easy_nextheader
- [X] curl_easy_option_by_id
- [X] curl_easy_option_by_name
- [X] curl_easy_option_next
- [ ] curl_easy_pause
- [ ] curl_easy_perform
- [ ] curl_easy_recv
- [X] curl_easy_reset
- [ ] curl_easy_send
- [ ] curl_easy_setopt
- [ ] curl_easy_strerror
- [ ] curl_easy_unescape
- [ ] curl_easy_upkeep
- [ ] curl_formadd
- [ ] curl_formfree
- [ ] curl_formget
- [ ] curl_free
- [ ] curl_getdate
- [ ] curl_global_cleanup
- [x] curl_global_init  --only default mode for now
- [ ] curl_global_init_mem
- [ ] curl_global_sslset
- [ ] curl_mime_addpart
- [ ] curl_mime_data
- [ ] curl_mime_data_cb
- [ ] curl_mime_encoder
- [ ] curl_mime_filedata
- [ ] curl_mime_filename
- [ ] curl_mime_free
- [ ] curl_mime_headers
- [ ] curl_mime_init
- [ ] curl_mime_name
- [ ] curl_mime_subparts
- [ ] curl_mime_type
- [ ] curl_multi_add_handle
- [ ] curl_multi_assign
- [ ] curl_multi_cleanup
- [ ] curl_multi_fdset
- [ ] curl_multi_info_read
- [ ] curl_multi_init
- [ ] curl_multi_perform
- [ ] curl_multi_remove_handle
- [ ] curl_multi_setopt
- [ ] curl_multi_socket_action
- [ ] curl_multi_strerror
- [ ] curl_multi_timeout
- [ ] curl_multi_poll
- [ ] curl_multi_wait
- [ ] curl_multi_wakeup
- [ ] curl_pushheader_byname
- [ ] curl_pushheader_bynum
- [ ] curl_share_cleanup
- [ ] curl_share_init
- [ ] curl_share_setopt
- [ ] curl_share_strerror
- [ ] curl_slist_append
- [ ] curl_slist_free_all
- [ ] curl_url
- [ ] curl_url_cleanup
- [ ] curl_url_dup
- [ ] curl_url_get
- [ ] curl_url_set
- [ ] curl_url_strerror
- [x] curl_version
- [x] curl_version_info
- [ ] curl_ws_recv
- [ ] curl_ws_send
- [ ] curl_ws_meta
