# About
This is an automatically generated file that keeps track of wrapper coverage of the ImGui API. This may not be 100% accurate as it is calculated programatically, but can serve as a good general idea of progress.

# Coverage
260 out of 395 API functions wrapped (**66% complete**)

| Function | Wrapped | Link | Notes |
| -------- | ------- | ---- | ----- |
| ImGui::CreateContext | ✅ | [imgui_api_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_api_gm.cpp#L8) | N/A |
| ImGui::DestroyContext | ✅ | [imgui_api_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_api_gm.cpp#L13) | N/A |
| ImGui::GetCurrentContext | ✅ | [imgui_api_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_api_gm.cpp#L20) | N/A |
| ImGui::SetCurrentContext | ✅ | [imgui_api_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_api_gm.cpp#L25) | N/A |
| ImGui::GetIO | ❌ | N/A | N/A |
| ImGui::GetStyle | ❌ | N/A | N/A |
| ImGui::NewFrame | ❌ | N/A | Handled internally by [__imgui_update function](https://github.com/nommiin/ImGui_GM/blob/main/dll/main.cpp#L63) |
| ImGui::EndFrame | ❌ | N/A | N/A |
| ImGui::Render | ❌ | N/A | Handled internally by [__imgui_render function](https://github.com/nommiin/ImGui_GM/blob/main/dll/main.cpp#L69) |
| ImGui::GetDrawData | ❌ | N/A | N/A |
| ImGui::ShowDemoWindow | ✅ | [imgui_api_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_api_gm.cpp#L32) | N/A |
| ImGui::ShowMetricsWindow | ✅ | [imgui_api_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_api_gm.cpp#L48) | N/A |
| ImGui::ShowDebugLogWindow | ✅ | [imgui_api_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_api_gm.cpp#L64) | N/A |
| ImGui::ShowStackToolWindow | ✅ | [imgui_api_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_api_gm.cpp#L80) | N/A |
| ImGui::ShowAboutWindow | ✅ | [imgui_api_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_api_gm.cpp#L96) | N/A |
| ImGui::ShowStyleEditor | ✅ | [imgui_api_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_api_gm.cpp#L112) | N/A |
| ImGui::ShowStyleSelector | ✅ | [imgui_api_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_api_gm.cpp#L117) | N/A |
| ImGui::ShowFontSelector | ✅ | [imgui_api_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_api_gm.cpp#L124) | N/A |
| ImGui::ShowUserGuide | ✅ | [imgui_api_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_api_gm.cpp#L131) | N/A |
| ImGui::GetVersion | ✅ | [imgui_api_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_api_gm.cpp#L136) | N/A |
| ImGui::StyleColorsDark | ✅ | [imgui_style_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_style_gm.cpp#L3) | N/A |
| ImGui::StyleColorsLight | ✅ | [imgui_style_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_style_gm.cpp#L8) | N/A |
| ImGui::StyleColorsClassic | ✅ | [imgui_style_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_style_gm.cpp#L13) | N/A |
| ImGui::Begin | ✅ | [imgui_window_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_window_gm.cpp#L3) | N/A |
| ImGui::End | ✅ | [imgui_window_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_window_gm.cpp#L24) | N/A |
| ImGui::BeginChild | ✅ | [imgui_window_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_window_gm.cpp#L29) | N/A |
| ImGui::BeginChild | ✅ | [imgui_window_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_window_gm.cpp#L29) | N/A |
| ImGui::EndChild | ✅ | [imgui_window_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_window_gm.cpp#L44) | N/A |
| ImGui::IsWindowAppearing | ✅ | [imgui_window_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_window_gm.cpp#L67) | N/A |
| ImGui::IsWindowCollapsed | ✅ | [imgui_window_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_window_gm.cpp#L72) | N/A |
| ImGui::IsWindowFocused | ✅ | [imgui_window_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_window_gm.cpp#L77) | N/A |
| ImGui::IsWindowHovered | ✅ | [imgui_window_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_window_gm.cpp#L85) | N/A |
| ImGui::GetWindowDrawList | ❌ | N/A | N/A |
| ImGui::GetWindowDpiScale | ✅ | [imgui_window_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_window_gm.cpp#L93) | N/A |
| ImGui::GetWindowPos | ❌ | N/A | ImVec2 returns are unsupported, use X/Y wrappers |
| ImGui::GetWindowSize | ❌ | N/A | ImVec2 returns are unsupported, use Width/Height wrappers |
| ImGui::GetWindowWidth | ✅ | [imgui_window_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_window_gm.cpp#L112) | N/A |
| ImGui::GetWindowHeight | ✅ | [imgui_window_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_window_gm.cpp#L117) | N/A |
| ImGui::GetWindowViewport | ❌ | N/A | N/A |
| ImGui::SetNextWindowPos | ✅ | [imgui_window_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_window_gm.cpp#L122) | N/A |
| ImGui::SetNextWindowSize | ✅ | [imgui_window_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_window_gm.cpp#L136) | N/A |
| ImGui::SetNextWindowSizeConstraints | ✅ | [imgui_window_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_window_gm.cpp#L146) | N/A |
| ImGui::SetNextWindowContentSize | ✅ | [imgui_window_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_window_gm.cpp#L157) | N/A |
| ImGui::SetNextWindowCollapsed | ✅ | [imgui_window_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_window_gm.cpp#L165) | N/A |
| ImGui::SetNextWindowFocus | ✅ | [imgui_window_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_window_gm.cpp#L174) | N/A |
| ImGui::SetNextWindowScroll | ✅ | [imgui_window_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_window_gm.cpp#L179) | N/A |
| ImGui::SetNextWindowBgAlpha | ✅ | [imgui_window_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_window_gm.cpp#L188) | N/A |
| ImGui::SetNextWindowViewport | ❌ | N/A | N/A |
| ImGui::SetWindowPos | ❌ | N/A | N/A |
| ImGui::SetWindowSize | ❌ | N/A | N/A |
| ImGui::SetWindowCollapsed | ❌ | N/A | N/A |
| ImGui::SetWindowFocus | ❌ | N/A | N/A |
| ImGui::SetWindowFontScale | ❌ | N/A | N/A |
| ImGui::SetWindowPos | ❌ | N/A | N/A |
| ImGui::SetWindowSize | ❌ | N/A | N/A |
| ImGui::SetWindowCollapsed | ❌ | N/A | N/A |
| ImGui::SetWindowFocus | ❌ | N/A | N/A |
| ImGui::GetContentRegionAvail | ❌ | N/A | ImVec2 returns are unsupported, use X/Y wrappers |
| ImGui::GetContentRegionMax | ❌ | N/A | ImVec2 returns are unsupported, use X/Y wrappers |
| ImGui::GetWindowContentRegionMin | ❌ | N/A | ImVec2 returns are unsupported, use X/Y wrappers |
| ImGui::GetWindowContentRegionMax | ❌ | N/A | ImVec2 returns are unsupported, use X/Y wrappers |
| ImGui::GetScrollX | ✅ | [imgui_window_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_window_gm.cpp#L195) | N/A |
| ImGui::GetScrollY | ✅ | [imgui_window_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_window_gm.cpp#L200) | N/A |
| ImGui::SetScrollX | ✅ | [imgui_window_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_window_gm.cpp#L205) | N/A |
| ImGui::SetScrollY | ✅ | [imgui_window_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_window_gm.cpp#L212) | N/A |
| ImGui::GetScrollMaxX | ✅ | [imgui_window_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_window_gm.cpp#L219) | N/A |
| ImGui::GetScrollMaxY | ✅ | [imgui_window_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_window_gm.cpp#L224) | N/A |
| ImGui::SetScrollHereX | ✅ | [imgui_window_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_window_gm.cpp#L229) | N/A |
| ImGui::SetScrollHereY | ✅ | [imgui_window_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_window_gm.cpp#L237) | N/A |
| ImGui::SetScrollFromPosX | ✅ | [imgui_window_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_window_gm.cpp#L245) | N/A |
| ImGui::SetScrollFromPosY | ✅ | [imgui_window_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_window_gm.cpp#L254) | N/A |
| ImGui::PushFont | ❌ | N/A | Fonts are currently unimplemented |
| ImGui::PopFont | ❌ | N/A | N/A |
| ImGui::PushStyleColor | ✅ | [imgui_style_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_style_gm.cpp#L18) | N/A |
| ImGui::PushStyleColor | ✅ | [imgui_style_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_style_gm.cpp#L18) | N/A |
| ImGui::PopStyleColor | ✅ | [imgui_style_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_style_gm.cpp#L27) | N/A |
| ImGui::PushStyleVar | ✅ | [imgui_style_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_style_gm.cpp#L35) | N/A |
| ImGui::PushStyleVar | ✅ | [imgui_style_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_style_gm.cpp#L35) | N/A |
| ImGui::PopStyleVar | ✅ | [imgui_style_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_style_gm.cpp#L49) | N/A |
| ImGui::PushAllowKeyboardFocus | ✅ | [imgui_api_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_api_gm.cpp#L347) | N/A |
| ImGui::PopAllowKeyboardFocus | ✅ | [imgui_api_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_api_gm.cpp#L354) | N/A |
| ImGui::PushButtonRepeat | ✅ | [imgui_api_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_api_gm.cpp#L367) | N/A |
| ImGui::PopButtonRepeat | ✅ | [imgui_api_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_api_gm.cpp#L374) | N/A |
| ImGui::PushItemWidth | ✅ | [imgui_layout_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_layout_gm.cpp#L215) | N/A |
| ImGui::PopItemWidth | ✅ | [imgui_layout_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_layout_gm.cpp#L222) | N/A |
| ImGui::SetNextItemWidth | ✅ | [imgui_layout_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_layout_gm.cpp#L227) | N/A |
| ImGui::CalcItemWidth | ✅ | [imgui_layout_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_layout_gm.cpp#L234) | N/A |
| ImGui::PushTextWrapPos | ✅ | [imgui_layout_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_layout_gm.cpp#L239) | N/A |
| ImGui::PopTextWrapPos | ✅ | [imgui_layout_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_layout_gm.cpp#L247) | N/A |
| ImGui::GetFont | ❌ | N/A | N/A |
| ImGui::GetFontSize | ✅ | [imgui_style_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_style_gm.cpp#L57) | N/A |
| ImGui::GetFontTexUvWhitePixel | ❌ | N/A | N/A |
| ImGui::GetColorU32 | ❌ | N/A | N/A |
| ImGui::GetColorU32 | ❌ | N/A | N/A |
| ImGui::GetColorU32 | ❌ | N/A | N/A |
| ImGui::GetStyleColorVec4 | ❌ | N/A | N/A |
| ImGui::Separator | ✅ | [imgui_layout_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_layout_gm.cpp#L30) | N/A |
| ImGui::SameLine | ✅ | [imgui_layout_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_layout_gm.cpp#L51) | N/A |
| ImGui::NewLine | ✅ | [imgui_layout_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_layout_gm.cpp#L20) | N/A |
| ImGui::Spacing | ✅ | [imgui_layout_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_layout_gm.cpp#L7) | N/A |
| ImGui::Dummy | ✅ | [imgui_layout_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_layout_gm.cpp#L12) | N/A |
| ImGui::Indent | ✅ | [imgui_layout_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_layout_gm.cpp#L35) | N/A |
| ImGui::Unindent | ✅ | [imgui_layout_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_layout_gm.cpp#L43) | N/A |
| ImGui::BeginGroup | ✅ | [imgui_layout_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_layout_gm.cpp#L61) | N/A |
| ImGui::EndGroup | ✅ | [imgui_layout_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_layout_gm.cpp#L66) | N/A |
| ImGui::GetCursorPos | ❌ | N/A | N/A |
| ImGui::GetCursorPosX | ✅ | [imgui_layout_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_layout_gm.cpp#L71) | N/A |
| ImGui::GetCursorPosY | ✅ | [imgui_layout_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_layout_gm.cpp#L76) | N/A |
| ImGui::SetCursorPos | ✅ | [imgui_layout_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_layout_gm.cpp#L117) | N/A |
| ImGui::SetCursorPosX | ✅ | [imgui_layout_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_layout_gm.cpp#L125) | N/A |
| ImGui::SetCursorPosY | ✅ | [imgui_layout_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_layout_gm.cpp#L132) | N/A |
| ImGui::GetCursorStartPos | ❌ | N/A | ImVec2 returns are unsupported, use X/Y wrappers |
| ImGui::GetCursorScreenPos | ❌ | N/A | ImVec2 returns are unsupported, use X/Y wrappers |
| ImGui::SetCursorScreenPos | ✅ | [imgui_layout_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_layout_gm.cpp#L109) | N/A |
| ImGui::AlignTextToFramePadding | ✅ | [imgui_layout_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_layout_gm.cpp#L25) | N/A |
| ImGui::GetTextLineHeight | ✅ | [imgui_layout_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_layout_gm.cpp#L139) | N/A |
| ImGui::GetTextLineHeightWithSpacing | ✅ | [imgui_layout_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_layout_gm.cpp#L144) | N/A |
| ImGui::GetFrameHeight | ✅ | [imgui_layout_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_layout_gm.cpp#L149) | N/A |
| ImGui::GetFrameHeightWithSpacing | ✅ | [imgui_layout_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_layout_gm.cpp#L154) | N/A |
| ImGui::PushID | ✅ | [imgui_api_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_api_gm.cpp#L143) | N/A |
| ImGui::PushID | ✅ | [imgui_api_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_api_gm.cpp#L143) | N/A |
| ImGui::PushID | ✅ | [imgui_api_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_api_gm.cpp#L143) | N/A |
| ImGui::PushID | ✅ | [imgui_api_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_api_gm.cpp#L143) | N/A |
| ImGui::PopID | ✅ | [imgui_api_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_api_gm.cpp#L155) | N/A |
| ImGui::GetID | ✅ | [imgui_api_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_api_gm.cpp#L160) | N/A |
| ImGui::GetID | ✅ | [imgui_api_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_api_gm.cpp#L160) | N/A |
| ImGui::GetID | ✅ | [imgui_api_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_api_gm.cpp#L160) | N/A |
| ImGui::TextUnformatted | ✅ | [imgui_text_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_text_gm.cpp#L3) | N/A |
| ImGui::Text | ✅ | [imgui_text_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_text_gm.cpp#L10) | N/A |
| ImGui::TextV | ❌ | N/A | Unsupported, use `string` function in GameMaker |
| ImGui::TextColored | ✅ | [imgui_text_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_text_gm.cpp#L17) | N/A |
| ImGui::TextColoredV | ❌ | N/A | Unsupported, use `string` function in GameMaker |
| ImGui::TextDisabled | ✅ | [imgui_text_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_text_gm.cpp#L27) | N/A |
| ImGui::TextDisabledV | ❌ | N/A | N/A |
| ImGui::TextWrapped | ✅ | [imgui_text_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_text_gm.cpp#L34) | N/A |
| ImGui::TextWrappedV | ❌ | N/A | Unsupported, use `string` function in GameMaker |
| ImGui::LabelText | ✅ | [imgui_text_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_text_gm.cpp#L41) | N/A |
| ImGui::LabelTextV | ❌ | N/A | Unsupported, use `string` function in GameMaker |
| ImGui::BulletText | ✅ | [imgui_text_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_text_gm.cpp#L49) | N/A |
| ImGui::BulletTextV | ❌ | N/A | Unsupported, use `string` function in GameMaker |
| ImGui::Button | ✅ | [imgui_widgets_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_widgets_gm.cpp#L7) | N/A |
| ImGui::SmallButton | ✅ | [imgui_widgets_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_widgets_gm.cpp#L18) | N/A |
| ImGui::InvisibleButton | ✅ | [imgui_widgets_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_widgets_gm.cpp#L25) | N/A |
| ImGui::ArrowButton | ✅ | [imgui_widgets_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_widgets_gm.cpp#L38) | N/A |
| ImGui::Checkbox | ✅ | [imgui_widgets_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_widgets_gm.cpp#L86) | N/A |
| ImGui::CheckboxFlags | ✅ | [imgui_widgets_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_widgets_gm.cpp#L95) | N/A |
| ImGui::CheckboxFlags | ✅ | [imgui_widgets_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_widgets_gm.cpp#L95) | N/A |
| ImGui::RadioButton | ✅ | [imgui_widgets_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_widgets_gm.cpp#L105) | N/A |
| ImGui::RadioButton | ✅ | [imgui_widgets_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_widgets_gm.cpp#L105) | N/A |
| ImGui::ProgressBar | ✅ | [imgui_widgets_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_widgets_gm.cpp#L114) | N/A |
| ImGui::Bullet | ✅ | [imgui_widgets_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_widgets_gm.cpp#L127) | N/A |
| ImGui::Image | ✅ | [imgui_widgets_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_widgets_gm.cpp#L46) | N/A |
| ImGui::ImageButton | ❌ | N/A | N/A |
| ImGui::BeginCombo | ✅ | [imgui_combo_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_combo_gm.cpp#L3) | N/A |
| ImGui::EndCombo | ✅ | [imgui_combo_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_combo_gm.cpp#L12) | N/A |
| ImGui::Combo | ✅ | [imgui_combo_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_combo_gm.cpp#L17) | N/A |
| ImGui::Combo | ✅ | [imgui_combo_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_combo_gm.cpp#L17) | N/A |
| ImGui::Combo | ✅ | [imgui_combo_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_combo_gm.cpp#L17) | N/A |
| ImGui::DragFloat | ✅ | [imgui_drag_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_drag_gm.cpp#L3) | N/A |
| ImGui::DragFloat2 | ✅ | [imgui_drag_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_drag_gm.cpp#L22) | N/A |
| ImGui::DragFloat3 | ✅ | [imgui_drag_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_drag_gm.cpp#L45) | N/A |
| ImGui::DragFloat4 | ✅ | [imgui_drag_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_drag_gm.cpp#L68) | N/A |
| ImGui::DragFloatRange2 | ✅ | [imgui_drag_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_drag_gm.cpp#L116) | N/A |
| ImGui::DragInt | ✅ | [imgui_drag_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_drag_gm.cpp#L140) | N/A |
| ImGui::DragInt2 | ✅ | [imgui_drag_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_drag_gm.cpp#L159) | N/A |
| ImGui::DragInt3 | ✅ | [imgui_drag_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_drag_gm.cpp#L182) | N/A |
| ImGui::DragInt4 | ✅ | [imgui_drag_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_drag_gm.cpp#L205) | N/A |
| ImGui::DragIntRange2 | ✅ | [imgui_drag_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_drag_gm.cpp#L253) | N/A |
| ImGui::DragScalar | ❌ | N/A | N/A |
| ImGui::DragScalarN | ❌ | N/A | N/A |
| ImGui::SliderFloat | ✅ | [imgui_slider_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_slider_gm.cpp#L3) | N/A |
| ImGui::SliderFloat2 | ✅ | [imgui_slider_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_slider_gm.cpp#L20) | N/A |
| ImGui::SliderFloat3 | ✅ | [imgui_slider_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_slider_gm.cpp#L41) | N/A |
| ImGui::SliderFloat4 | ✅ | [imgui_slider_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_slider_gm.cpp#L62) | N/A |
| ImGui::SliderAngle | ✅ | [imgui_slider_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_slider_gm.cpp#L249) | N/A |
| ImGui::SliderInt | ✅ | [imgui_slider_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_slider_gm.cpp#L108) | N/A |
| ImGui::SliderInt2 | ✅ | [imgui_slider_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_slider_gm.cpp#L125) | N/A |
| ImGui::SliderInt3 | ✅ | [imgui_slider_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_slider_gm.cpp#L146) | N/A |
| ImGui::SliderInt4 | ✅ | [imgui_slider_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_slider_gm.cpp#L167) | N/A |
| ImGui::SliderScalar | ❌ | N/A | N/A |
| ImGui::SliderScalarN | ❌ | N/A | N/A |
| ImGui::VSliderFloat | ✅ | [imgui_slider_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_slider_gm.cpp#L211) | N/A |
| ImGui::VSliderInt | ✅ | [imgui_slider_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_slider_gm.cpp#L230) | N/A |
| ImGui::VSliderScalar | ❌ | N/A | N/A |
| ImGui::InputText | ✅ | [imgui_input_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_input_gm.cpp#L3) | N/A |
| ImGui::InputTextMultiline | ✅ | [imgui_input_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_input_gm.cpp#L16) | N/A |
| ImGui::InputTextWithHint | ✅ | [imgui_input_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_input_gm.cpp#L33) | N/A |
| ImGui::InputFloat | ✅ | [imgui_input_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_input_gm.cpp#L47) | N/A |
| ImGui::InputFloat2 | ✅ | [imgui_input_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_input_gm.cpp#L64) | N/A |
| ImGui::InputFloat3 | ✅ | [imgui_input_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_input_gm.cpp#L85) | N/A |
| ImGui::InputFloat4 | ✅ | [imgui_input_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_input_gm.cpp#L106) | N/A |
| ImGui::InputInt | ✅ | [imgui_input_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_input_gm.cpp#L150) | N/A |
| ImGui::InputInt2 | ✅ | [imgui_input_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_input_gm.cpp#L165) | N/A |
| ImGui::InputInt3 | ✅ | [imgui_input_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_input_gm.cpp#L180) | N/A |
| ImGui::InputInt4 | ✅ | [imgui_input_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_input_gm.cpp#L195) | N/A |
| ImGui::InputDouble | ✅ | [imgui_input_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_input_gm.cpp#L227) | N/A |
| ImGui::InputScalar | ❌ | N/A | N/A |
| ImGui::InputScalarN | ❌ | N/A | N/A |
| ImGui::ColorEdit3 | ✅ | [imgui_color_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_color_gm.cpp#L6) | N/A |
| ImGui::ColorEdit4 | ✅ | [imgui_color_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_color_gm.cpp#L30) | N/A |
| ImGui::ColorPicker3 | ✅ | [imgui_color_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_color_gm.cpp#L18) | N/A |
| ImGui::ColorPicker4 | ✅ | [imgui_color_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_color_gm.cpp#L60) | N/A |
| ImGui::ColorButton | ✅ | [imgui_color_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_color_gm.cpp#L90) | N/A |
| ImGui::SetColorEditOptions | ✅ | [imgui_color_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_color_gm.cpp#L106) | N/A |
| ImGui::TreeNode | ✅ | [imgui_tree_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_tree_gm.cpp#L3) | N/A |
| ImGui::TreeNode | ✅ | [imgui_tree_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_tree_gm.cpp#L3) | N/A |
| ImGui::TreeNode | ✅ | [imgui_tree_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_tree_gm.cpp#L3) | N/A |
| ImGui::TreeNodeV | ❌ | N/A | N/A |
| ImGui::TreeNodeV | ❌ | N/A | N/A |
| ImGui::TreeNodeEx | ✅ | [imgui_tree_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_tree_gm.cpp#L10) | N/A |
| ImGui::TreeNodeEx | ✅ | [imgui_tree_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_tree_gm.cpp#L10) | N/A |
| ImGui::TreeNodeEx | ✅ | [imgui_tree_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_tree_gm.cpp#L10) | N/A |
| ImGui::TreeNodeExV | ❌ | N/A | N/A |
| ImGui::TreeNodeExV | ❌ | N/A | N/A |
| ImGui::TreePush | ✅ | [imgui_tree_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_tree_gm.cpp#L19) | N/A |
| ImGui::TreePush | ✅ | [imgui_tree_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_tree_gm.cpp#L19) | N/A |
| ImGui::TreePop | ✅ | [imgui_tree_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_tree_gm.cpp#L26) | N/A |
| ImGui::GetTreeNodeToLabelSpacing | ✅ | [imgui_tree_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_tree_gm.cpp#L31) | N/A |
| ImGui::CollapsingHeader | ✅ | [imgui_tree_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_tree_gm.cpp#L45) | N/A |
| ImGui::CollapsingHeader | ✅ | [imgui_tree_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_tree_gm.cpp#L45) | N/A |
| ImGui::SetNextItemOpen | ✅ | [imgui_tree_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_tree_gm.cpp#L36) | N/A |
| ImGui::Selectable | ✅ | [imgui_selectable_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_selectable_gm.cpp#L3) | N/A |
| ImGui::Selectable | ✅ | [imgui_selectable_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_selectable_gm.cpp#L3) | N/A |
| ImGui::BeginListBox | ✅ | [imgui_listbox_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_listbox_gm.cpp#L3) | N/A |
| ImGui::EndListBox | ✅ | [imgui_listbox_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_listbox_gm.cpp#L14) | N/A |
| ImGui::ListBox | ✅ | [imgui_listbox_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_listbox_gm.cpp#L19) | N/A |
| ImGui::ListBox | ✅ | [imgui_listbox_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_listbox_gm.cpp#L19) | N/A |
| ImGui::PlotLines | ✅ | [imgui_plots_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_plots_gm.cpp#L3) | N/A |
| ImGui::PlotLines | ✅ | [imgui_plots_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_plots_gm.cpp#L3) | N/A |
| ImGui::PlotHistogram | ✅ | [imgui_plots_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_plots_gm.cpp#L25) | N/A |
| ImGui::PlotHistogram | ✅ | [imgui_plots_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_plots_gm.cpp#L25) | N/A |
| ImGui::Value | ✅ | [imgui_text_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_text_gm.cpp#L56) | N/A |
| ImGui::Value | ✅ | [imgui_text_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_text_gm.cpp#L56) | N/A |
| ImGui::Value | ✅ | [imgui_text_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_text_gm.cpp#L56) | N/A |
| ImGui::Value | ✅ | [imgui_text_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_text_gm.cpp#L56) | N/A |
| ImGui::BeginMenuBar | ✅ | [imgui_menu_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_menu_gm.cpp#L3) | N/A |
| ImGui::EndMenuBar | ✅ | [imgui_menu_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_menu_gm.cpp#L8) | N/A |
| ImGui::BeginMainMenuBar | ✅ | [imgui_menu_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_menu_gm.cpp#L13) | N/A |
| ImGui::EndMainMenuBar | ✅ | [imgui_menu_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_menu_gm.cpp#L18) | N/A |
| ImGui::BeginMenu | ✅ | [imgui_menu_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_menu_gm.cpp#L23) | N/A |
| ImGui::EndMenu | ✅ | [imgui_menu_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_menu_gm.cpp#L32) | N/A |
| ImGui::MenuItem | ✅ | [imgui_menu_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_menu_gm.cpp#L37) | N/A |
| ImGui::MenuItem | ✅ | [imgui_menu_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_menu_gm.cpp#L37) | N/A |
| ImGui::BeginTooltip | ✅ | [imgui_tooltips_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_tooltips_gm.cpp#L3) | N/A |
| ImGui::EndTooltip | ✅ | [imgui_tooltips_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_tooltips_gm.cpp#L8) | N/A |
| ImGui::SetTooltip | ✅ | [imgui_tooltips_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_tooltips_gm.cpp#L13) | N/A |
| ImGui::SetTooltipV | ❌ | N/A | N/A |
| ImGui::BeginPopup | ✅ | [imgui_popup_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_popup_gm.cpp#L3) | N/A |
| ImGui::BeginPopupModal | ✅ | [imgui_popup_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_popup_gm.cpp#L12) | N/A |
| ImGui::EndPopup | ✅ | [imgui_popup_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_popup_gm.cpp#L33) | N/A |
| ImGui::OpenPopup | ✅ | [imgui_popup_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_popup_gm.cpp#L38) | N/A |
| ImGui::OpenPopup | ✅ | [imgui_popup_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_popup_gm.cpp#L38) | N/A |
| ImGui::OpenPopupOnItemClick | ✅ | [imgui_popup_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_popup_gm.cpp#L47) | N/A |
| ImGui::CloseCurrentPopup | ✅ | [imgui_popup_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_popup_gm.cpp#L61) | N/A |
| ImGui::BeginPopupContextItem | ✅ | [imgui_popup_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_popup_gm.cpp#L66) | N/A |
| ImGui::BeginPopupContextWindow | ✅ | [imgui_popup_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_popup_gm.cpp#L80) | N/A |
| ImGui::BeginPopupContextVoid | ✅ | [imgui_popup_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_popup_gm.cpp#L94) | N/A |
| ImGui::IsPopupOpen | ✅ | [imgui_popup_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_popup_gm.cpp#L108) | N/A |
| ImGui::BeginTable | ✅ | [imgui_table_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_table_gm.cpp#L3) | N/A |
| ImGui::EndTable | ✅ | [imgui_table_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_table_gm.cpp#L19) | N/A |
| ImGui::TableNextRow | ✅ | [imgui_table_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_table_gm.cpp#L24) | N/A |
| ImGui::TableNextColumn | ✅ | [imgui_table_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_table_gm.cpp#L34) | N/A |
| ImGui::TableSetColumnIndex | ✅ | [imgui_table_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_table_gm.cpp#L39) | N/A |
| ImGui::TableSetupColumn | ✅ | [imgui_table_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_table_gm.cpp#L46) | N/A |
| ImGui::TableSetupScrollFreeze | ✅ | [imgui_table_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_table_gm.cpp#L59) | N/A |
| ImGui::TableHeadersRow | ✅ | [imgui_table_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_table_gm.cpp#L67) | N/A |
| ImGui::TableHeader | ✅ | [imgui_table_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_table_gm.cpp#L72) | N/A |
| ImGui::TableGetSortSpecs | ❌ | N/A | N/A |
| ImGui::TableGetColumnCount | ✅ | [imgui_table_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_table_gm.cpp#L79) | N/A |
| ImGui::TableGetColumnIndex | ✅ | [imgui_table_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_table_gm.cpp#L84) | N/A |
| ImGui::TableGetRowIndex | ✅ | [imgui_table_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_table_gm.cpp#L106) | N/A |
| ImGui::TableGetColumnName | ✅ | [imgui_table_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_table_gm.cpp#L89) | N/A |
| ImGui::TableGetColumnFlags | ✅ | [imgui_table_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_table_gm.cpp#L98) | N/A |
| ImGui::TableSetColumnEnabled | ✅ | [imgui_table_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_table_gm.cpp#L111) | N/A |
| ImGui::TableSetBgColor | ✅ | [imgui_table_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_table_gm.cpp#L119) | N/A |
| ImGui::Columns | ❌ | N/A | N/A |
| ImGui::NextColumn | ❌ | N/A | N/A |
| ImGui::GetColumnIndex | ❌ | N/A | N/A |
| ImGui::GetColumnWidth | ❌ | N/A | N/A |
| ImGui::SetColumnWidth | ❌ | N/A | N/A |
| ImGui::GetColumnOffset | ❌ | N/A | N/A |
| ImGui::SetColumnOffset | ❌ | N/A | N/A |
| ImGui::GetColumnsCount | ❌ | N/A | N/A |
| ImGui::BeginTabBar | ✅ | [imgui_tabs_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_tabs_gm.cpp#L3) | N/A |
| ImGui::EndTabBar | ✅ | [imgui_tabs_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_tabs_gm.cpp#L12) | N/A |
| ImGui::BeginTabItem | ✅ | [imgui_tabs_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_tabs_gm.cpp#L17) | N/A |
| ImGui::EndTabItem | ✅ | [imgui_tabs_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_tabs_gm.cpp#L38) | N/A |
| ImGui::TabItemButton | ✅ | [imgui_tabs_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_tabs_gm.cpp#L43) | N/A |
| ImGui::SetTabItemClosed | ✅ | [imgui_tabs_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_tabs_gm.cpp#L52) | N/A |
| ImGui::DockSpace | ✅ | [imgui_docking_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_docking_gm.cpp#L3) | N/A |
| ImGui::DockSpaceOverViewport | ✅ | [imgui_docking_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_docking_gm.cpp#L17) | N/A |
| ImGui::SetNextWindowDockID | ✅ | [imgui_docking_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_docking_gm.cpp#L27) | N/A |
| ImGui::SetNextWindowClass | ✅ | [imgui_docking_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_docking_gm.cpp#L36) | N/A |
| ImGui::GetWindowDockID | ✅ | [imgui_docking_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_docking_gm.cpp#L41) | N/A |
| ImGui::IsWindowDocked | ✅ | [imgui_docking_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_docking_gm.cpp#L46) | N/A |
| ImGui::LogToTTY | ❌ | N/A | N/A |
| ImGui::LogToFile | ❌ | N/A | N/A |
| ImGui::LogToClipboard | ❌ | N/A | N/A |
| ImGui::LogFinish | ❌ | N/A | N/A |
| ImGui::LogButtons | ❌ | N/A | N/A |
| ImGui::LogText | ❌ | N/A | N/A |
| ImGui::LogTextV | ❌ | N/A | N/A |
| ImGui::BeginDragDropSource | ❌ | N/A | N/A |
| ImGui::SetDragDropPayload | ❌ | N/A | N/A |
| ImGui::EndDragDropSource | ❌ | N/A | N/A |
| ImGui::BeginDragDropTarget | ❌ | N/A | N/A |
| ImGui::AcceptDragDropPayload | ❌ | N/A | N/A |
| ImGui::EndDragDropTarget | ❌ | N/A | N/A |
| ImGui::GetDragDropPayload | ❌ | N/A | N/A |
| ImGui::BeginDisabled | ✅ | [imgui_api_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_api_gm.cpp#L167) | N/A |
| ImGui::EndDisabled | ✅ | [imgui_api_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_api_gm.cpp#L175) | N/A |
| ImGui::PushClipRect | ✅ | [imgui_layout_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_layout_gm.cpp#L252) | N/A |
| ImGui::PopClipRect | ✅ | [imgui_layout_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_layout_gm.cpp#L263) | N/A |
| ImGui::SetItemDefaultFocus | ✅ | [imgui_api_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_api_gm.cpp#L379) | N/A |
| ImGui::SetKeyboardFocusHere | ✅ | [imgui_api_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_api_gm.cpp#L359) | N/A |
| ImGui::IsItemHovered | ✅ | [imgui_api_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_api_gm.cpp#L180) | N/A |
| ImGui::IsItemActive | ✅ | [imgui_api_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_api_gm.cpp#L188) | N/A |
| ImGui::IsItemFocused | ✅ | [imgui_api_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_api_gm.cpp#L193) | N/A |
| ImGui::IsItemClicked | ✅ | [imgui_api_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_api_gm.cpp#L198) | N/A |
| ImGui::IsItemVisible | ✅ | [imgui_api_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_api_gm.cpp#L206) | N/A |
| ImGui::IsItemEdited | ✅ | [imgui_api_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_api_gm.cpp#L211) | N/A |
| ImGui::IsItemActivated | ✅ | [imgui_api_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_api_gm.cpp#L216) | N/A |
| ImGui::IsItemDeactivated | ✅ | [imgui_api_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_api_gm.cpp#L221) | N/A |
| ImGui::IsItemDeactivatedAfterEdit | ✅ | [imgui_api_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_api_gm.cpp#L226) | N/A |
| ImGui::IsItemToggledOpen | ✅ | [imgui_api_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_api_gm.cpp#L231) | N/A |
| ImGui::IsAnyItemHovered | ✅ | [imgui_api_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_api_gm.cpp#L236) | N/A |
| ImGui::IsAnyItemActive | ✅ | [imgui_api_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_api_gm.cpp#L241) | N/A |
| ImGui::IsAnyItemFocused | ✅ | [imgui_api_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_api_gm.cpp#L246) | N/A |
| ImGui::GetItemID | ✅ | [imgui_api_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_api_gm.cpp#L251) | N/A |
| ImGui::GetItemRectMin | ❌ | N/A | N/A |
| ImGui::GetItemRectMax | ❌ | N/A | N/A |
| ImGui::GetItemRectSize | ❌ | N/A | N/A |
| ImGui::SetItemAllowOverlap | ✅ | [imgui_api_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_api_gm.cpp#L298) | N/A |
| ImGui::GetMainViewport | ❌ | N/A | N/A |
| ImGui::GetBackgroundDrawList | ❌ | N/A | N/A |
| ImGui::GetForegroundDrawList | ❌ | N/A | N/A |
| ImGui::GetBackgroundDrawList | ❌ | N/A | N/A |
| ImGui::GetForegroundDrawList | ❌ | N/A | N/A |
| ImGui::IsRectVisible | ✅ | [imgui_api_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_api_gm.cpp#L303) | N/A |
| ImGui::IsRectVisible | ✅ | [imgui_api_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_api_gm.cpp#L303) | N/A |
| ImGui::GetTime | ✅ | [imgui_api_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_api_gm.cpp#L313) | N/A |
| ImGui::GetFrameCount | ✅ | [imgui_api_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_api_gm.cpp#L318) | N/A |
| ImGui::GetDrawListSharedData | ❌ | N/A | N/A |
| ImGui::GetStyleColorName | ✅ | [imgui_style_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_style_gm.cpp#L69) | N/A |
| ImGui::SetStateStorage | ❌ | N/A | N/A |
| ImGui::GetStateStorage | ❌ | N/A | N/A |
| ImGui::BeginChildFrame | ✅ | [imgui_window_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_window_gm.cpp#L49) | N/A |
| ImGui::EndChildFrame | ✅ | [imgui_window_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_window_gm.cpp#L62) | N/A |
| ImGui::CalcTextSize | ❌ | N/A | N/A |
| ImGui::ColorConvertU32ToFloat4 | ❌ | N/A | N/A |
| ImGui::ColorConvertFloat4ToU32 | ❌ | N/A | N/A |
| ImGui::ColorConvertRGBtoHSV | ❌ | N/A | N/A |
| ImGui::ColorConvertHSVtoRGB | ❌ | N/A | N/A |
| ImGui::IsKeyDown | ❌ | N/A | N/A |
| ImGui::IsKeyPressed | ❌ | N/A | N/A |
| ImGui::IsKeyReleased | ❌ | N/A | N/A |
| ImGui::GetKeyPressedAmount | ❌ | N/A | N/A |
| ImGui::GetKeyName | ❌ | N/A | N/A |
| ImGui::SetNextFrameWantCaptureKeyboard | ❌ | N/A | N/A |
| ImGui::Shortcut | ❌ | N/A | N/A |
| ImGui::IsMouseDown | ❌ | N/A | N/A |
| ImGui::IsMouseClicked | ❌ | N/A | N/A |
| ImGui::IsMouseReleased | ❌ | N/A | N/A |
| ImGui::IsMouseDoubleClicked | ❌ | N/A | N/A |
| ImGui::GetMouseClickedCount | ❌ | N/A | N/A |
| ImGui::IsMouseHoveringRect | ❌ | N/A | N/A |
| ImGui::IsMousePosValid | ❌ | N/A | N/A |
| ImGui::IsAnyMouseDown | ❌ | N/A | N/A |
| ImGui::GetMousePos | ❌ | N/A | N/A |
| ImGui::GetMousePosOnOpeningCurrentPopup | ❌ | N/A | N/A |
| ImGui::IsMouseDragging | ❌ | N/A | N/A |
| ImGui::GetMouseDragDelta | ❌ | N/A | N/A |
| ImGui::ResetMouseDragDelta | ❌ | N/A | N/A |
| ImGui::GetMouseCursor | ❌ | N/A | N/A |
| ImGui::SetMouseCursor | ❌ | N/A | N/A |
| ImGui::SetNextFrameWantCaptureMouse | ❌ | N/A | N/A |
| ImGui::GetClipboardText | ❌ | N/A | N/A |
| ImGui::SetClipboardText | ❌ | N/A | N/A |
| ImGui::LoadIniSettingsFromDisk | ❌ | N/A | N/A |
| ImGui::LoadIniSettingsFromMemory | ❌ | N/A | N/A |
| ImGui::SaveIniSettingsToDisk | ❌ | N/A | N/A |
| ImGui::SaveIniSettingsToMemory | ❌ | N/A | N/A |
| ImGui::DebugTextEncoding | ❌ | N/A | N/A |
| ImGui::DebugCheckVersionAndDataLayout | ❌ | N/A | N/A |
| ImGui::SetAllocatorFunctions | ❌ | N/A | N/A |
| ImGui::GetAllocatorFunctions | ❌ | N/A | N/A |
| ImGui::MemAlloc | ❌ | N/A | N/A |
| ImGui::MemFree | ❌ | N/A | N/A |
| ImGui::GetPlatformIO | ❌ | N/A | N/A |
| ImGui::UpdatePlatformWindows | ❌ | N/A | N/A |
| ImGui::RenderPlatformWindowsDefault | ❌ | N/A | N/A |
| ImGui::DestroyPlatformWindows | ❌ | N/A | N/A |
| ImGui::FindViewportByID | ❌ | N/A | N/A |
| ImGui::FindViewportByPlatformHandle | ❌ | N/A | N/A |
| ImGui::GetKeyIndex | ❌ | N/A | N/A |

# Non-Standard
Below is a table of non-standard functions made specifically for ImGui_GM

| Function | Link |
| -------- | ---- |
| ImGui.GetItemRectMinX() | [imgui_api_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_api_gm.cpp#L256) |
| ImGui.GetItemRectMinY() | [imgui_api_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_api_gm.cpp#L263) |
| ImGui.GetItemRectMaxX() | [imgui_api_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_api_gm.cpp#L270) |
| ImGui.GetItemRectMaxY() | [imgui_api_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_api_gm.cpp#L277) |
| ImGui.GetItemRectSizeX() | [imgui_api_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_api_gm.cpp#L284) |
| ImGui.GetItemRectSizeY() | [imgui_api_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_api_gm.cpp#L291) |
| ImGui.CalcTextWidth(text, hide_text_after_double_hash, wrap_width) | [imgui_api_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_api_gm.cpp#L323) |
| ImGui.CalcTextHeight(text, hide_text_after_double_hash, wrap_width) | [imgui_api_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_api_gm.cpp#L335) |
| ImGui.DragFloatN(label, v, count, v_speed, v_min, v_max, format, flags) | [imgui_drag_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_drag_gm.cpp#L91) |
| ImGui.DragIntN(label, v, count, v_speed, v_min, v_max, format, flags) | [imgui_drag_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_drag_gm.cpp#L228) |
| ImGui.InputFloatN(label, v, count, step, step_fast, format, flags) | [imgui_input_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_input_gm.cpp#L127) |
| ImGui.InputIntN(label, v, count, flags) | [imgui_input_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_input_gm.cpp#L210) |
| ImGui.GetCursorStartPosX() | [imgui_layout_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_layout_gm.cpp#L81) |
| ImGui.GetCursorStartPosY() | [imgui_layout_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_layout_gm.cpp#L88) |
| ImGui.GetCursorScreenPosX() | [imgui_layout_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_layout_gm.cpp#L95) |
| ImGui.GetCursorScreenPosY() | [imgui_layout_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_layout_gm.cpp#L102) |
| ImGui.GetContentRegionAvailX() | [imgui_layout_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_layout_gm.cpp#L159) |
| ImGui.GetContentRegionAvailY() | [imgui_layout_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_layout_gm.cpp#L166) |
| ImGui.GetContentRegionMaxX() | [imgui_layout_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_layout_gm.cpp#L173) |
| ImGui.GetContentRegionMaxY() | [imgui_layout_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_layout_gm.cpp#L180) |
| ImGui.GetWindowContentRegionMinX() | [imgui_layout_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_layout_gm.cpp#L187) |
| ImGui.GetWindowContentRegionMinY() | [imgui_layout_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_layout_gm.cpp#L194) |
| ImGui.GetWindowContentRegionMaxX() | [imgui_layout_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_layout_gm.cpp#L201) |
| ImGui.GetWindowContentRegionMaxY() | [imgui_layout_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_layout_gm.cpp#L208) |
| ImGui.SliderFloatN(label, v, count, v_speed, v_min, v_max, format, flags) | [imgui_slider_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_slider_gm.cpp#L83) |
| ImGui.SliderIntN(label, v, count, v_min, v_max, format, flags) | [imgui_slider_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_slider_gm.cpp#L188) |
| ImGui.GetStyleColor(idx) | [imgui_style_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_style_gm.cpp#L62) |
| ImGui.Surface(surface, color, alpha, width, height, uv) | [imgui_widgets_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_widgets_gm.cpp#L66) |
| ImGui.GetWindowPosX() | [imgui_window_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_window_gm.cpp#L98) |
| ImGui.GetWindowPosY() | [imgui_window_gm.cpp](https://github.com/nommiin/ImGui_GM/blob/main/dll/imgui_window_gm.cpp#L105) |