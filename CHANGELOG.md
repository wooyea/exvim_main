# Changelog

## 0.3.0 (developing)

## New Features

 - Integrate ex-hierarchy plugin for generate hierarchy map of classes.
 - Add `folder_filter_root_only` filter option in .exvim file. 
 - Add `GSW` method in ex-gsearch. This method will allow user global search
   single word instead of text.
 - Add `<leader><esc>` which can directly close last opened plugin window no
   matter where your cursor live.

## Changes

 - Replace `g:exvim_dev` and `g:exvim_dev_path` with g:exvim_custom_path. This allow user specific the exvim directory for install. 

## Bug Fixes

 - Fix [Issue #44](https://github.com/exvim/main/issues/44): Error message is thrown when `:Update` and excluded folder is missing
