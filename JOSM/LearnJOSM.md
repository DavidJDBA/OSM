      <!DOCTYPE html>
      <html>
        <head>
            <meta charset="utf-8" />
            <title>LearnJOSM</title>
            <style>.markdown-preview:not([data-use-github-style]) { padding: 2em; font-size: 1.2em; color: rgb(171, 178, 191); background-color: rgb(40, 44, 52); overflow: auto; }
.markdown-preview:not([data-use-github-style]) > :first-child { margin-top: 0px; }
.markdown-preview:not([data-use-github-style]) h1, .markdown-preview:not([data-use-github-style]) h2, .markdown-preview:not([data-use-github-style]) h3, .markdown-preview:not([data-use-github-style]) h4, .markdown-preview:not([data-use-github-style]) h5, .markdown-preview:not([data-use-github-style]) h6 { line-height: 1.2; margin-top: 1.5em; margin-bottom: 0.5em; color: rgb(255, 255, 255); }
.markdown-preview:not([data-use-github-style]) h1 { font-size: 2.4em; font-weight: 300; }
.markdown-preview:not([data-use-github-style]) h2 { font-size: 1.8em; font-weight: 400; }
.markdown-preview:not([data-use-github-style]) h3 { font-size: 1.5em; font-weight: 500; }
.markdown-preview:not([data-use-github-style]) h4 { font-size: 1.2em; font-weight: 600; }
.markdown-preview:not([data-use-github-style]) h5 { font-size: 1.1em; font-weight: 600; }
.markdown-preview:not([data-use-github-style]) h6 { font-size: 1em; font-weight: 600; }
.markdown-preview:not([data-use-github-style]) strong { color: rgb(255, 255, 255); }
.markdown-preview:not([data-use-github-style]) del { color: rgb(124, 135, 156); }
.markdown-preview:not([data-use-github-style]) a, .markdown-preview:not([data-use-github-style]) a code { color: rgb(82, 139, 255); }
.markdown-preview:not([data-use-github-style]) img { max-width: 100%; }
.markdown-preview:not([data-use-github-style]) > p { margin-top: 0px; margin-bottom: 1.5em; }
.markdown-preview:not([data-use-github-style]) > ul, .markdown-preview:not([data-use-github-style]) > ol { margin-bottom: 1.5em; }
.markdown-preview:not([data-use-github-style]) blockquote { margin: 1.5em 0px; font-size: inherit; color: rgb(124, 135, 156); border-color: rgb(75, 83, 98); border-width: 4px; }
.markdown-preview:not([data-use-github-style]) hr { margin: 3em 0px; border-top: 2px dashed rgb(75, 83, 98); background: none; }
.markdown-preview:not([data-use-github-style]) table { margin: 1.5em 0px; }
.markdown-preview:not([data-use-github-style]) th { color: rgb(255, 255, 255); }
.markdown-preview:not([data-use-github-style]) th, .markdown-preview:not([data-use-github-style]) td { padding: 0.66em 1em; border: 1px solid rgb(75, 83, 98); }
.markdown-preview:not([data-use-github-style]) code { color: rgb(255, 255, 255); background-color: rgb(58, 63, 75); }
.markdown-preview:not([data-use-github-style]) pre.editor-colors { margin: 1.5em 0px; padding: 1em; font-size: 0.92em; border-radius: 3px; background-color: rgb(49, 54, 63); }
.markdown-preview:not([data-use-github-style]) kbd { color: rgb(255, 255, 255); border-width: 1px 1px 2px; border-style: solid; border-color: rgb(75, 83, 98) rgb(75, 83, 98) rgb(62, 68, 81); border-image: initial; background-color: rgb(58, 63, 75); }
.markdown-preview[data-use-github-style] { font-family: "Helvetica Neue", Helvetica, "Segoe UI", Arial, freesans, sans-serif; line-height: 1.6; overflow-wrap: break-word; padding: 30px; font-size: 16px; color: rgb(51, 51, 51); background-color: rgb(255, 255, 255); overflow: scroll; }
.markdown-preview[data-use-github-style] > :first-child { margin-top: 0px !important; }
.markdown-preview[data-use-github-style] > :last-child { margin-bottom: 0px !important; }
.markdown-preview[data-use-github-style] a:not([href]) { color: inherit; text-decoration: none; }
.markdown-preview[data-use-github-style] .absent { color: rgb(204, 0, 0); }
.markdown-preview[data-use-github-style] .anchor { position: absolute; top: 0px; left: 0px; display: block; padding-right: 6px; padding-left: 30px; margin-left: -30px; }
.markdown-preview[data-use-github-style] .anchor:focus { outline: none; }
.markdown-preview[data-use-github-style] h1, .markdown-preview[data-use-github-style] h2, .markdown-preview[data-use-github-style] h3, .markdown-preview[data-use-github-style] h4, .markdown-preview[data-use-github-style] h5, .markdown-preview[data-use-github-style] h6 { position: relative; margin-top: 1em; margin-bottom: 16px; font-weight: bold; line-height: 1.4; }
.markdown-preview[data-use-github-style] h1 .octicon-link, .markdown-preview[data-use-github-style] h2 .octicon-link, .markdown-preview[data-use-github-style] h3 .octicon-link, .markdown-preview[data-use-github-style] h4 .octicon-link, .markdown-preview[data-use-github-style] h5 .octicon-link, .markdown-preview[data-use-github-style] h6 .octicon-link { display: none; color: rgb(0, 0, 0); vertical-align: middle; }
.markdown-preview[data-use-github-style] h1:hover .anchor, .markdown-preview[data-use-github-style] h2:hover .anchor, .markdown-preview[data-use-github-style] h3:hover .anchor, .markdown-preview[data-use-github-style] h4:hover .anchor, .markdown-preview[data-use-github-style] h5:hover .anchor, .markdown-preview[data-use-github-style] h6:hover .anchor { padding-left: 8px; margin-left: -30px; text-decoration: none; }
.markdown-preview[data-use-github-style] h1:hover .anchor .octicon-link, .markdown-preview[data-use-github-style] h2:hover .anchor .octicon-link, .markdown-preview[data-use-github-style] h3:hover .anchor .octicon-link, .markdown-preview[data-use-github-style] h4:hover .anchor .octicon-link, .markdown-preview[data-use-github-style] h5:hover .anchor .octicon-link, .markdown-preview[data-use-github-style] h6:hover .anchor .octicon-link { display: inline-block; }
.markdown-preview[data-use-github-style] h1 tt, .markdown-preview[data-use-github-style] h2 tt, .markdown-preview[data-use-github-style] h3 tt, .markdown-preview[data-use-github-style] h4 tt, .markdown-preview[data-use-github-style] h5 tt, .markdown-preview[data-use-github-style] h6 tt, .markdown-preview[data-use-github-style] h1 code, .markdown-preview[data-use-github-style] h2 code, .markdown-preview[data-use-github-style] h3 code, .markdown-preview[data-use-github-style] h4 code, .markdown-preview[data-use-github-style] h5 code, .markdown-preview[data-use-github-style] h6 code { font-size: inherit; }
.markdown-preview[data-use-github-style] h1 { padding-bottom: 0.3em; font-size: 2.25em; line-height: 1.2; border-bottom: 1px solid rgb(238, 238, 238); }
.markdown-preview[data-use-github-style] h1 .anchor { line-height: 1; }
.markdown-preview[data-use-github-style] h2 { padding-bottom: 0.3em; font-size: 1.75em; line-height: 1.225; border-bottom: 1px solid rgb(238, 238, 238); }
.markdown-preview[data-use-github-style] h2 .anchor { line-height: 1; }
.markdown-preview[data-use-github-style] h3 { font-size: 1.5em; line-height: 1.43; }
.markdown-preview[data-use-github-style] h3 .anchor { line-height: 1.2; }
.markdown-preview[data-use-github-style] h4 { font-size: 1.25em; }
.markdown-preview[data-use-github-style] h4 .anchor { line-height: 1.2; }
.markdown-preview[data-use-github-style] h5 { font-size: 1em; }
.markdown-preview[data-use-github-style] h5 .anchor { line-height: 1.1; }
.markdown-preview[data-use-github-style] h6 { font-size: 1em; color: rgb(119, 119, 119); }
.markdown-preview[data-use-github-style] h6 .anchor { line-height: 1.1; }
.markdown-preview[data-use-github-style] p, .markdown-preview[data-use-github-style] blockquote, .markdown-preview[data-use-github-style] ul, .markdown-preview[data-use-github-style] ol, .markdown-preview[data-use-github-style] dl, .markdown-preview[data-use-github-style] table, .markdown-preview[data-use-github-style] pre { margin-top: 0px; margin-bottom: 16px; }
.markdown-preview[data-use-github-style] hr { height: 4px; padding: 0px; margin: 16px 0px; background-color: rgb(231, 231, 231); border: 0px none; }
.markdown-preview[data-use-github-style] ul, .markdown-preview[data-use-github-style] ol { padding-left: 2em; }
.markdown-preview[data-use-github-style] ul.no-list, .markdown-preview[data-use-github-style] ol.no-list { padding: 0px; list-style-type: none; }
.markdown-preview[data-use-github-style] ul ul, .markdown-preview[data-use-github-style] ul ol, .markdown-preview[data-use-github-style] ol ol, .markdown-preview[data-use-github-style] ol ul { margin-top: 0px; margin-bottom: 0px; }
.markdown-preview[data-use-github-style] li > p { margin-top: 16px; }
.markdown-preview[data-use-github-style] dl { padding: 0px; }
.markdown-preview[data-use-github-style] dl dt { padding: 0px; margin-top: 16px; font-size: 1em; font-style: italic; font-weight: bold; }
.markdown-preview[data-use-github-style] dl dd { padding: 0px 16px; margin-bottom: 16px; }
.markdown-preview[data-use-github-style] blockquote { padding: 0px 15px; color: rgb(119, 119, 119); border-left: 4px solid rgb(221, 221, 221); }
.markdown-preview[data-use-github-style] blockquote > :first-child { margin-top: 0px; }
.markdown-preview[data-use-github-style] blockquote > :last-child { margin-bottom: 0px; }
.markdown-preview[data-use-github-style] table { display: block; width: 100%; overflow: auto; word-break: keep-all; }
.markdown-preview[data-use-github-style] table th { font-weight: bold; }
.markdown-preview[data-use-github-style] table th, .markdown-preview[data-use-github-style] table td { padding: 6px 13px; border: 1px solid rgb(221, 221, 221); }
.markdown-preview[data-use-github-style] table tr { background-color: rgb(255, 255, 255); border-top: 1px solid rgb(204, 204, 204); }
.markdown-preview[data-use-github-style] table tr:nth-child(2n) { background-color: rgb(248, 248, 248); }
.markdown-preview[data-use-github-style] img { max-width: 100%; box-sizing: border-box; }
.markdown-preview[data-use-github-style] .emoji { max-width: none; }
.markdown-preview[data-use-github-style] span.frame { display: block; overflow: hidden; }
.markdown-preview[data-use-github-style] span.frame > span { display: block; float: left; width: auto; padding: 7px; margin: 13px 0px 0px; overflow: hidden; border: 1px solid rgb(221, 221, 221); }
.markdown-preview[data-use-github-style] span.frame span img { display: block; float: left; }
.markdown-preview[data-use-github-style] span.frame span span { display: block; padding: 5px 0px 0px; clear: both; color: rgb(51, 51, 51); }
.markdown-preview[data-use-github-style] span.align-center { display: block; overflow: hidden; clear: both; }
.markdown-preview[data-use-github-style] span.align-center > span { display: block; margin: 13px auto 0px; overflow: hidden; text-align: center; }
.markdown-preview[data-use-github-style] span.align-center span img { margin: 0px auto; text-align: center; }
.markdown-preview[data-use-github-style] span.align-right { display: block; overflow: hidden; clear: both; }
.markdown-preview[data-use-github-style] span.align-right > span { display: block; margin: 13px 0px 0px; overflow: hidden; text-align: right; }
.markdown-preview[data-use-github-style] span.align-right span img { margin: 0px; text-align: right; }
.markdown-preview[data-use-github-style] span.float-left { display: block; float: left; margin-right: 13px; overflow: hidden; }
.markdown-preview[data-use-github-style] span.float-left span { margin: 13px 0px 0px; }
.markdown-preview[data-use-github-style] span.float-right { display: block; float: right; margin-left: 13px; overflow: hidden; }
.markdown-preview[data-use-github-style] span.float-right > span { display: block; margin: 13px auto 0px; overflow: hidden; text-align: right; }
.markdown-preview[data-use-github-style] code, .markdown-preview[data-use-github-style] tt { padding: 0.2em 0px; margin: 0px; font-size: 85%; background-color: rgba(0, 0, 0, 0.04); border-radius: 3px; }
.markdown-preview[data-use-github-style] code::before, .markdown-preview[data-use-github-style] tt::before, .markdown-preview[data-use-github-style] code::after, .markdown-preview[data-use-github-style] tt::after { letter-spacing: -0.2em; content: " "; }
.markdown-preview[data-use-github-style] code br, .markdown-preview[data-use-github-style] tt br { display: none; }
.markdown-preview[data-use-github-style] del code { text-decoration: inherit; }
.markdown-preview[data-use-github-style] pre > code { padding: 0px; margin: 0px; font-size: 100%; word-break: normal; white-space: pre; background: transparent; border: 0px; }
.markdown-preview[data-use-github-style] .highlight { margin-bottom: 16px; }
.markdown-preview[data-use-github-style] .highlight pre, .markdown-preview[data-use-github-style] pre { padding: 16px; overflow: auto; font-size: 85%; line-height: 1.45; background-color: rgb(247, 247, 247); border-radius: 3px; }
.markdown-preview[data-use-github-style] .highlight pre { margin-bottom: 0px; word-break: normal; }
.markdown-preview[data-use-github-style] pre { overflow-wrap: normal; }
.markdown-preview[data-use-github-style] pre code, .markdown-preview[data-use-github-style] pre tt { display: inline; max-width: initial; padding: 0px; margin: 0px; overflow: initial; line-height: inherit; overflow-wrap: normal; background-color: transparent; border: 0px; }
.markdown-preview[data-use-github-style] pre code::before, .markdown-preview[data-use-github-style] pre tt::before, .markdown-preview[data-use-github-style] pre code::after, .markdown-preview[data-use-github-style] pre tt::after { content: normal; }
.markdown-preview[data-use-github-style] kbd { display: inline-block; padding: 3px 5px; font-size: 11px; line-height: 10px; color: rgb(85, 85, 85); vertical-align: middle; background-color: rgb(252, 252, 252); border-width: 1px; border-style: solid; border-color: rgb(204, 204, 204) rgb(204, 204, 204) rgb(187, 187, 187); border-image: initial; border-radius: 3px; box-shadow: rgb(187, 187, 187) 0px -1px 0px inset; }
.markdown-preview[data-use-github-style] a { color: rgb(51, 122, 183); }
.markdown-preview[data-use-github-style] code { color: inherit; }
.markdown-preview[data-use-github-style] pre.editor-colors { padding: 0.8em 1em; margin-bottom: 1em; font-size: 0.85em; border-radius: 4px; overflow: auto; }
.markdown-preview pre.editor-colors { user-select: auto; }
.scrollbars-visible-always .markdown-preview pre.editor-colors .vertical-scrollbar, .scrollbars-visible-always .markdown-preview pre.editor-colors .horizontal-scrollbar { visibility: hidden; }
.scrollbars-visible-always .markdown-preview pre.editor-colors:hover .vertical-scrollbar, .scrollbars-visible-always .markdown-preview pre.editor-colors:hover .horizontal-scrollbar { visibility: visible; }
.markdown-preview .task-list-item input[type="checkbox"] { position: absolute; margin: 0.25em 0px 0px -1.4em; }
.markdown-preview .task-list-item { list-style-type: none; }
.bracket-matcher .region {
  border-bottom: 1px dotted lime;
  position: absolute;
}
.line-number.bracket-matcher.bracket-matcher {
  color: #abb2bf;
  background-color: #3a3f4b;
}

.spell-check-misspelling .region {
  border-bottom: 2px dotted rgba(255, 51, 51, 0.75);
}
.spell-check-corrections {
  width: 25em !important;
}

pre.editor-colors {
  background-color: #282c34;
  color: #abb2bf;
}
pre.editor-colors .line.cursor-line {
  background-color: rgba(153, 187, 255, 0.04);
}
pre.editor-colors .invisible {
  color: #abb2bf;
}
pre.editor-colors .cursor {
  border-left: 2px solid #528bff;
}
pre.editor-colors .selection .region {
  background-color: #3e4451;
}
pre.editor-colors .bracket-matcher .region {
  border-bottom: 1px solid #528bff;
  box-sizing: border-box;
}
pre.editor-colors .invisible-character {
  color: rgba(171, 178, 191, 0.15);
}
pre.editor-colors .indent-guide {
  color: rgba(171, 178, 191, 0.15);
}
pre.editor-colors .wrap-guide {
  background-color: rgba(171, 178, 191, 0.15);
}
pre.editor-colors .find-result .region.region.region,
pre.editor-colors .current-result .region.region.region {
  border-radius: 2px;
  background-color: rgba(82, 139, 255, 0.24);
  transition: border-color 0.4s;
}
pre.editor-colors .find-result .region.region.region {
  border: 2px solid transparent;
}
pre.editor-colors .current-result .region.region.region {
  border: 2px solid #528bff;
  transition-duration: .1s;
}
pre.editor-colors .gutter .line-number {
  color: #636d83;
  -webkit-font-smoothing: antialiased;
}
pre.editor-colors .gutter .line-number.cursor-line {
  color: #abb2bf;
  background-color: #3a3f4b;
}
pre.editor-colors .gutter .line-number.cursor-line-no-selection {
  background-color: transparent;
}
pre.editor-colors .gutter .line-number .icon-right {
  color: #abb2bf;
}
pre.editor-colors .gutter:not(.git-diff-icon) .line-number.git-line-removed.git-line-removed::before {
  bottom: -3px;
}
pre.editor-colors .gutter:not(.git-diff-icon) .line-number.git-line-removed::after {
  content: "";
  position: absolute;
  left: 0px;
  bottom: 0px;
  width: 25px;
  border-bottom: 1px dotted rgba(224, 82, 82, 0.5);
  pointer-events: none;
}
pre.editor-colors .gutter .line-number.folded,
pre.editor-colors .gutter .line-number:after,
pre.editor-colors .fold-marker:after {
  color: #abb2bf;
}
.syntax--comment {
  color: #5c6370;
  font-style: italic;
}
.syntax--comment .syntax--markup.syntax--link {
  color: #5c6370;
}
.syntax--entity.syntax--name.syntax--type {
  color: #e5c07b;
}
.syntax--entity.syntax--other.syntax--inherited-class {
  color: #e5c07b;
}
.syntax--keyword {
  color: #c678dd;
}
.syntax--keyword.syntax--control {
  color: #c678dd;
}
.syntax--keyword.syntax--operator {
  color: #c678dd;
}
.syntax--keyword.syntax--other.syntax--special-method {
  color: #61afef;
}
.syntax--keyword.syntax--other.syntax--unit {
  color: #d19a66;
}
.syntax--storage {
  color: #c678dd;
}
.syntax--storage.syntax--type.syntax--annotation,
.syntax--storage.syntax--type.syntax--primitive {
  color: #c678dd;
}
.syntax--storage.syntax--modifier.syntax--package,
.syntax--storage.syntax--modifier.syntax--import {
  color: #abb2bf;
}
.syntax--constant {
  color: #d19a66;
}
.syntax--constant.syntax--variable {
  color: #d19a66;
}
.syntax--constant.syntax--character.syntax--escape {
  color: #56b6c2;
}
.syntax--constant.syntax--numeric {
  color: #d19a66;
}
.syntax--constant.syntax--other.syntax--color {
  color: #56b6c2;
}
.syntax--constant.syntax--other.syntax--symbol {
  color: #56b6c2;
}
.syntax--variable {
  color: #e06c75;
}
.syntax--variable.syntax--interpolation {
  color: #be5046;
}
.syntax--variable.syntax--parameter {
  color: #abb2bf;
}
.syntax--string {
  color: #98c379;
}
.syntax--string > .syntax--source,
.syntax--string .syntax--embedded {
  color: #abb2bf;
}
.syntax--string.syntax--regexp {
  color: #56b6c2;
}
.syntax--string.syntax--regexp .syntax--source.syntax--ruby.syntax--embedded {
  color: #e5c07b;
}
.syntax--string.syntax--other.syntax--link {
  color: #e06c75;
}
.syntax--punctuation.syntax--definition.syntax--comment {
  color: #5c6370;
}
.syntax--punctuation.syntax--definition.syntax--method-parameters,
.syntax--punctuation.syntax--definition.syntax--function-parameters,
.syntax--punctuation.syntax--definition.syntax--parameters,
.syntax--punctuation.syntax--definition.syntax--separator,
.syntax--punctuation.syntax--definition.syntax--seperator,
.syntax--punctuation.syntax--definition.syntax--array {
  color: #abb2bf;
}
.syntax--punctuation.syntax--definition.syntax--heading,
.syntax--punctuation.syntax--definition.syntax--identity {
  color: #61afef;
}
.syntax--punctuation.syntax--definition.syntax--bold {
  color: #e5c07b;
  font-weight: bold;
}
.syntax--punctuation.syntax--definition.syntax--italic {
  color: #c678dd;
  font-style: italic;
}
.syntax--punctuation.syntax--section.syntax--embedded {
  color: #be5046;
}
.syntax--punctuation.syntax--section.syntax--method,
.syntax--punctuation.syntax--section.syntax--class,
.syntax--punctuation.syntax--section.syntax--inner-class {
  color: #abb2bf;
}
.syntax--support.syntax--class {
  color: #e5c07b;
}
.syntax--support.syntax--type {
  color: #56b6c2;
}
.syntax--support.syntax--function {
  color: #56b6c2;
}
.syntax--support.syntax--function.syntax--any-method {
  color: #61afef;
}
.syntax--entity.syntax--name.syntax--function {
  color: #61afef;
}
.syntax--entity.syntax--name.syntax--class,
.syntax--entity.syntax--name.syntax--type.syntax--class {
  color: #e5c07b;
}
.syntax--entity.syntax--name.syntax--section {
  color: #61afef;
}
.syntax--entity.syntax--name.syntax--tag {
  color: #e06c75;
}
.syntax--entity.syntax--other.syntax--attribute-name {
  color: #d19a66;
}
.syntax--entity.syntax--other.syntax--attribute-name.syntax--id {
  color: #61afef;
}
.syntax--meta.syntax--class {
  color: #e5c07b;
}
.syntax--meta.syntax--class.syntax--body {
  color: #abb2bf;
}
.syntax--meta.syntax--method-call,
.syntax--meta.syntax--method {
  color: #abb2bf;
}
.syntax--meta.syntax--definition.syntax--variable {
  color: #e06c75;
}
.syntax--meta.syntax--link {
  color: #d19a66;
}
.syntax--meta.syntax--require {
  color: #61afef;
}
.syntax--meta.syntax--selector {
  color: #c678dd;
}
.syntax--meta.syntax--separator {
  color: #abb2bf;
}
.syntax--meta.syntax--tag {
  color: #abb2bf;
}
.syntax--underline {
  text-decoration: underline;
}
.syntax--none {
  color: #abb2bf;
}
.syntax--invalid.syntax--deprecated {
  color: #523d14 !important;
  background-color: #e0c285 !important;
}
.syntax--invalid.syntax--illegal {
  color: white !important;
  background-color: #e05252 !important;
}
.syntax--markup.syntax--bold {
  color: #d19a66;
  font-weight: bold;
}
.syntax--markup.syntax--changed {
  color: #c678dd;
}
.syntax--markup.syntax--deleted {
  color: #e06c75;
}
.syntax--markup.syntax--italic {
  color: #c678dd;
  font-style: italic;
}
.syntax--markup.syntax--heading {
  color: #e06c75;
}
.syntax--markup.syntax--heading .syntax--punctuation.syntax--definition.syntax--heading {
  color: #61afef;
}
.syntax--markup.syntax--link {
  color: #56b6c2;
}
.syntax--markup.syntax--inserted {
  color: #98c379;
}
.syntax--markup.syntax--quote {
  color: #d19a66;
}
.syntax--markup.syntax--raw {
  color: #98c379;
}
.syntax--source.syntax--c .syntax--keyword.syntax--operator {
  color: #c678dd;
}
.syntax--source.syntax--cpp .syntax--keyword.syntax--operator {
  color: #c678dd;
}
.syntax--source.syntax--cs .syntax--keyword.syntax--operator {
  color: #c678dd;
}
.syntax--source.syntax--css .syntax--property-name,
.syntax--source.syntax--css .syntax--property-value {
  color: #828997;
}
.syntax--source.syntax--css .syntax--property-name.syntax--support,
.syntax--source.syntax--css .syntax--property-value.syntax--support {
  color: #abb2bf;
}
.syntax--source.syntax--elixir .syntax--source.syntax--embedded.syntax--source {
  color: #abb2bf;
}
.syntax--source.syntax--elixir .syntax--constant.syntax--language,
.syntax--source.syntax--elixir .syntax--constant.syntax--numeric,
.syntax--source.syntax--elixir .syntax--constant.syntax--definition {
  color: #61afef;
}
.syntax--source.syntax--elixir .syntax--variable.syntax--definition,
.syntax--source.syntax--elixir .syntax--variable.syntax--anonymous {
  color: #c678dd;
}
.syntax--source.syntax--elixir .syntax--parameter.syntax--variable.syntax--function {
  color: #d19a66;
  font-style: italic;
}
.syntax--source.syntax--elixir .syntax--quoted {
  color: #98c379;
}
.syntax--source.syntax--elixir .syntax--keyword.syntax--special-method,
.syntax--source.syntax--elixir .syntax--embedded.syntax--section,
.syntax--source.syntax--elixir .syntax--embedded.syntax--source.syntax--empty {
  color: #e06c75;
}
.syntax--source.syntax--elixir .syntax--readwrite.syntax--module .syntax--punctuation {
  color: #e06c75;
}
.syntax--source.syntax--elixir .syntax--regexp.syntax--section,
.syntax--source.syntax--elixir .syntax--regexp.syntax--string {
  color: #be5046;
}
.syntax--source.syntax--elixir .syntax--separator,
.syntax--source.syntax--elixir .syntax--keyword.syntax--operator {
  color: #d19a66;
}
.syntax--source.syntax--elixir .syntax--variable.syntax--constant {
  color: #e5c07b;
}
.syntax--source.syntax--elixir .syntax--array,
.syntax--source.syntax--elixir .syntax--scope,
.syntax--source.syntax--elixir .syntax--section {
  color: #828997;
}
.syntax--source.syntax--gfm .syntax--markup {
  -webkit-font-smoothing: auto;
}
.syntax--source.syntax--gfm .syntax--link .syntax--entity {
  color: #61afef;
}
.syntax--source.syntax--go .syntax--storage.syntax--type.syntax--string {
  color: #c678dd;
}
.syntax--source.syntax--ini .syntax--keyword.syntax--other.syntax--definition.syntax--ini {
  color: #e06c75;
}
.syntax--source.syntax--java .syntax--storage.syntax--modifier.syntax--import {
  color: #e5c07b;
}
.syntax--source.syntax--java .syntax--storage.syntax--type {
  color: #e5c07b;
}
.syntax--source.syntax--java .syntax--keyword.syntax--operator.syntax--instanceof {
  color: #c678dd;
}
.syntax--source.syntax--java-properties .syntax--meta.syntax--key-pair {
  color: #e06c75;
}
.syntax--source.syntax--java-properties .syntax--meta.syntax--key-pair > .syntax--punctuation {
  color: #abb2bf;
}
.syntax--source.syntax--js .syntax--keyword.syntax--operator {
  color: #56b6c2;
}
.syntax--source.syntax--js .syntax--keyword.syntax--operator.syntax--delete,
.syntax--source.syntax--js .syntax--keyword.syntax--operator.syntax--in,
.syntax--source.syntax--js .syntax--keyword.syntax--operator.syntax--of,
.syntax--source.syntax--js .syntax--keyword.syntax--operator.syntax--instanceof,
.syntax--source.syntax--js .syntax--keyword.syntax--operator.syntax--new,
.syntax--source.syntax--js .syntax--keyword.syntax--operator.syntax--typeof,
.syntax--source.syntax--js .syntax--keyword.syntax--operator.syntax--void {
  color: #c678dd;
}
.syntax--source.syntax--ts .syntax--keyword.syntax--operator {
  color: #56b6c2;
}
.syntax--source.syntax--flow .syntax--keyword.syntax--operator {
  color: #56b6c2;
}
.syntax--source.syntax--json .syntax--meta.syntax--structure.syntax--dictionary.syntax--json > .syntax--string.syntax--quoted.syntax--json {
  color: #e06c75;
}
.syntax--source.syntax--json .syntax--meta.syntax--structure.syntax--dictionary.syntax--json > .syntax--string.syntax--quoted.syntax--json > .syntax--punctuation.syntax--string {
  color: #e06c75;
}
.syntax--source.syntax--json .syntax--meta.syntax--structure.syntax--dictionary.syntax--json > .syntax--value.syntax--json > .syntax--string.syntax--quoted.syntax--json,
.syntax--source.syntax--json .syntax--meta.syntax--structure.syntax--array.syntax--json > .syntax--value.syntax--json > .syntax--string.syntax--quoted.syntax--json,
.syntax--source.syntax--json .syntax--meta.syntax--structure.syntax--dictionary.syntax--json > .syntax--value.syntax--json > .syntax--string.syntax--quoted.syntax--json > .syntax--punctuation,
.syntax--source.syntax--json .syntax--meta.syntax--structure.syntax--array.syntax--json > .syntax--value.syntax--json > .syntax--string.syntax--quoted.syntax--json > .syntax--punctuation {
  color: #98c379;
}
.syntax--source.syntax--json .syntax--meta.syntax--structure.syntax--dictionary.syntax--json > .syntax--constant.syntax--language.syntax--json,
.syntax--source.syntax--json .syntax--meta.syntax--structure.syntax--array.syntax--json > .syntax--constant.syntax--language.syntax--json {
  color: #56b6c2;
}
.syntax--ng.syntax--interpolation {
  color: #e06c75;
}
.syntax--ng.syntax--interpolation.syntax--begin,
.syntax--ng.syntax--interpolation.syntax--end {
  color: #61afef;
}
.syntax--ng.syntax--interpolation .syntax--function {
  color: #e06c75;
}
.syntax--ng.syntax--interpolation .syntax--function.syntax--begin,
.syntax--ng.syntax--interpolation .syntax--function.syntax--end {
  color: #61afef;
}
.syntax--ng.syntax--interpolation .syntax--bool {
  color: #d19a66;
}
.syntax--ng.syntax--interpolation .syntax--bracket {
  color: #abb2bf;
}
.syntax--ng.syntax--pipe,
.syntax--ng.syntax--operator {
  color: #abb2bf;
}
.syntax--ng.syntax--tag {
  color: #56b6c2;
}
.syntax--ng.syntax--attribute-with-value .syntax--attribute-name {
  color: #e5c07b;
}
.syntax--ng.syntax--attribute-with-value .syntax--string {
  color: #c678dd;
}
.syntax--ng.syntax--attribute-with-value .syntax--string.syntax--begin,
.syntax--ng.syntax--attribute-with-value .syntax--string.syntax--end {
  color: #abb2bf;
}
.syntax--source.syntax--ruby .syntax--constant.syntax--other.syntax--symbol > .syntax--punctuation {
  color: inherit;
}
.syntax--source.syntax--php .syntax--class.syntax--bracket {
  color: #abb2bf;
}
.syntax--source.syntax--python .syntax--keyword.syntax--operator.syntax--logical.syntax--python {
  color: #c678dd;
}
.syntax--source.syntax--python .syntax--variable.syntax--parameter {
  color: #d19a66;
}
</style>
        </head>
        <body class='markdown-preview' data-use-github-style><h1 id="using-the-josm-editor">Using the JOSM editor</h1>
<h3 id="by-david-jenne">by David Jenne</h3>
<h2 id="getting-started">Getting Started</h2>
<h4 id="installation">Installation</h4>
<ol>
<li><p>An OpenStreetMap Logon is required for editing maps.  If you do not have an account, go to <a href="https://www.openstreetmap.org/user/new">OpenStreetMap</a> and sign up.</p>
</li>
<li><p>Download and install JOSM.  For installation go to <a href="https://josm.openstreetmap.de/">JOSM</a>.</p>
</li>
<li><p>Update Plug-ins and core as recommended.</p>
<p>Look for a "You should update" message when opening JOSM.<br>In this example, the current version (15937) is out-of-date when compared with the latest stable release (16239).
<img alt="You should Update Message" src="C:\Users\dave\Documents\Projects\OSM\Learning_JOSM\YouShouldUpdate.jpg">  </p>
<p>A Windows Installer and a Mac Package should be available for the installation and updates.  Update Plugins if this appears:<br><img alt="Update Plugins" src="C:\Users\dave\Documents\Projects\OSM\Learning_JOSM\PluginUpdate.jpg"></p>
</li>
</ol>
<h4 id="learning-josm">Learning JOSM</h4>
<p>This document gives some examples from Weld County, Colorado.  There are plenty of other areas in need of additional entries or fixes.  For more information about using JOSM and specific instructions, see the <a href="https://wiki.openstreetmap.org/wiki/JOSM/Guide">JOSM Guide</a>.</p>
<p>Another good basic tutorial is at <a href="https://learnosm.org/en/josm/start-josm/">Getting Started With JOSM</a>.</p>
<h2 id="connecting-to-openstreetmap">Connecting to OpenStreetMap</h2>
<p>  With an active account, select <strong><em>Edit-&gt;Preferences</em></strong> from the menu and select the tab with the Globe.  Enter your account and password, choosing between OAuth and plain text password authentication.</p>
<p>  <img alt="Password Entry" src="C:\Users\dave\Documents\Projects\OSM\Learning_JOSM\UserPassword.jpg">  </p>
<p>  Use the green download arrow to select an area for mapping.  <img alt="Download Arrow" src="C:\Users\dave\Documents\Projects\OSM\Learning_JOSM\DownloadArrow.jpg">  </p>
<p>  For this tutorial:  </p>
<ul>
<li><p>Find an area with a variety of data types (roads, buildings, natural features).</p>
</li>
<li><p><em>With multiple users practicing this at once, please select different locations.</em></p>
</li>
<li><p>JOSM uses the right mouse button for navigation and the left for selecting and/or editing.</p>
<p><img alt="Download" src="C:\Users\dave\Documents\Projects\OSM\Learning_JOSM\WeldDownload.jpg"></p>
<p>Use the left mouse button to draw a box covering the area chosen for editing.  Press the "Download" button.  If the area is too large a message will appear; in that case draw a smaller box.</p>
<p>Use the <strong><em>Imagery</em></strong> menu item to download background imagery.  In much of Colorado, Bing seems to have the most up-to-date imagery while ESRI Clarity (Beta) shows a large amount of detail.  Another option is to use USGS maps.  This is good for special purposes, such as verifying tags, but is generally not the best for tracing.</p>
<p><img alt="JOSM Startup" src="C:\Users\dave\Documents\Projects\OSM\Learning_JOSM\JOSMStartup.jpg"></p>
</li>
</ul>
<h2 id="navigation-selection-and-editing">Navigation, Selection and Editing</h2>
<h4 id="navigating">Navigating</h4>
<p>  The right mouse button can be used to navigate throughout the downloaded area.  Latitude and longitude are shown in the lower left.  </p>
<p>  Move the map using right mouse button click and drag (Windows).  The scroll wheel or the plus and minus keys can be used to zoom in and out.  As can the slider bar in the upper left.  </p>
<p>  <img alt="Scale Slider" src="C:\Users\dave\Documents\Projects\OSM\Learning_JOSM\ScaleSlider.jpg"></p>
<h4 id="selection">Selection</h4>
<p>  Unlike the ID editor, which has separate Point, Line and Area drawing tools and for selection, JOSM has only two such options, adding (or editing) and selection.  These can be activated with the <strong><em>S</em></strong> key for selection and the <strong><em>A</em></strong> key for adding.  There are also tool  buttons for these.</p>
<p>  <img alt="SelectAdd" src="C:\Users\dave\Documents\Projects\OSM\Learning_JOSM\SelectAdd.jpg"></p>
<p>  For a specific location the latitude or longitude display can be left-clicked and a new location/scale entered.  <img alt="JumpToPosition" src="C:\Users\dave\Documents\Projects\OSM\Learning_JOSM\JumpToPosition.jpg"></p>
<p>  Select an object and note the tags.  These can be edited or changed.  In this example, County Road 388 has been selected.  Some of the tags should be edited so they comply with OSM standards.  Also there are some other features that can be aligned or added (roads, trees, farmland).
  <img alt="Example0" src="C:\Users\dave\Documents\Projects\OSM\Learning_JOSM\CoRd388_example0.jpg"></p>
<p>  This example is from 40.38576, -104.47000</p>
<h4 id="editing-or-adding-tags">Editing or Adding Tags</h4>
<p>  In this example, the highway value should be changed from <strong><em>residential</em></strong> to "<strong><em>unclassified</em></strong>.  A "residential" designation is reserved for roads through residential neighborhoods that may have restrictions, such as lower speed limits, unless they merit a higher level designation (e.g. tertiary).  Also, if the name, etc. has been verified in person or using some other public open source (not Google maps), the <strong><em>tiger:reviewed = no</em></strong> tag can be deleted.</p>
<p>  <img alt="Example1" src="C:\Users\dave\Documents\Projects\OSM\Learning_JOSM\CoRd388_example1.jpg">
  In the <strong><em>Tags: .../ Memberships</em></strong> window (right panel) use the <strong><em>+Add</em></strong> button for new tags, <strong><em>Edit</em></strong> to change the value of an existing tag or <strong><em>Delete</em></strong> to remove it completely.</p>
<h4 id="adding-and-fixing-features">Adding and Fixing Features</h4>
<p>The location at (40.4356666, -104.5099944) needs some work. Several buildings, roads and other features could be added.  Plus the county roads and their intersection are misaligned.</p>
<p><img alt="Example 2A" src="C:\Users\dave\Documents\Projects\OSM\Learning_JOSM\Example2A.jpg"></p>
<p>Begin editing by pressing the <strong><em>A</em></strong> key or use the <strong><em>Draw Nodes</em></strong> <img alt="DrawNodes" src="C:\Users\dave\Documents\Projects\OSM\Learning_JOSM\DrawNodes.jpg"> button in JOSM.  To add a single node (e.g. for a tree or other small feature), simply double click at the new location.  This will add the feature and leave it selected.  Use the <strong><em>Tags: .../ Memberships</em></strong> window to add appropriate tags and values.  </p>
<p>Draw new ways or linear features beginning with a left click and clicking again where the way turns or bends.  If a node is currently selected, the drawing will start at that point.  Press the esc key if it's an incorrect starting point or you do not want to include it in your new line.  Double click to complete drawing. If the way starts at the terminal node of another way, it will extend that way.  If that is not desired, start a new way and later join to the old node.  </p>
<p>To add a closed area (e.g. a building or parking lot), simply draw a way or line and finish at the starting point. Press the <strong><em>Q</em></strong> key to square the sides.  Here we have added a house and then pressed the Add button in order to tag the new feature.
<img alt="Example 2C" src="C:\Users\dave\Documents\Projects\OSM\Learning_JOSM\Example2C.jpg"></p>
<p>The property at the intersection is missing some service roads, and several of the other roads are misaligned.  To align the roads, select the individual nodes and drag them to the proper position.   Be careful!  If the entire way is selected (highlighted in red), it will be moved.  There are handles (+ signs) between nodes on each way (if zoomed in enough). Grabbing and moving one of these will create a brand new node at its new location.</p>
<p>Here, we have moved the node at County Roads 62 and 59 to the middle of the intersection, dragged a handle on Highway 62 to its center and have edited the value of the highway tag.  Unless it's in a residential neighborhood, a public road of less than tertiary ranking should be tagged as "unclassified".  Also, several buildings and a service road have now been added.
<img alt="Example 2D" src="C:\Users\dave\Documents\Projects\OSM\Learning_JOSM\Example2D.jpg"></p>
<h2 id="other-editing-techniques">Other Editing Techniques</h2>
<h4 id="copy-and-paste">Copy and Paste</h4>
<p>The standard <strong><em>Ctrl-C, Ctrl-V</em></strong> combination works in JOSM.  Copying and pasting an object will preserve its geometry and tags.  But either of these can be edited in the copy.<br>Alternatively, all similar objects can be selected at once and the tags edited together.</p>
<p>In this example, there are two silos side-by-side.  Start adding a silo by drawing a triangle at its location.</p>
<p><img alt="Silos 1" src="C:\Users\dave\Documents\Projects\OSM\Learning_JOSM\Silos1.jpg"></p>
<p>With the new triangle selected, press Shift-O to transform it into a circle.  Tags can be added at this point or later:   <strong><em>man_made: silo</em></strong>.</p>
<p><img alt="Silos 2" src="C:\Users\dave\Documents\Projects\OSM\Learning_JOSM\Silos2.jpg"></p>
<p>To duplicate the object, press <strong><em>Ctrl-C</em></strong>, move the cursor to the new location and press <strong><em>Ctrl-V</em></strong> to paste it there.  Each structure should be placed so that its trace corresponds with its intersection with the ground. With differing camera angles, the roof may appear offset from the ground location.</p>
<p><img alt="Silos3" src="C:\Users\dave\Documents\Projects\OSM\Learning_JOSM\Silos3.jpg"></p>
<p>If tags have not been entered yet,  select one object and then any others using <strong><em>Shift-Left Click</em></strong>.  Use the <strong><em>Tags ... / Membersips</em></strong> window to add or edit the tags for all selected objects simultaneously</p>
<p><img alt="Silos4" src="C:\Users\dave\Documents\Projects\OSM\Learning_JOSM\Silos4.jpg"></p>
<h4 id="combining-and-splitting-ways">Combining and Splitting ways</h4>
<p>The intersection of Weld County Roads 59 and 66 is at 40.464695 latitude and -104.50708033 longitude.  The east-west County Road 66 is tagged as a service road west of County Road 59 and residential east of 59.  Both sides are the same (although usage and conditions may differ) and should be tagged as "unclassified".  To combine these, select one and <strong><em>Shift-Left-Click</em></strong> to select and highlight the other as well.  To combine the two ways, press <strong><em>C</em></strong> key or the <strong><em>Combine Several Ways into One</em></strong> button shown here.  <img alt="Merge.jpg" src="C:\Users\dave\Documents\Projects\OSM\Learning_JOSM\Merge.jpg"></p>
<p>This will combine several ways into one, but it may also prompt a dialog for resolving conflicts.  </p>
<p><img alt="Example 2E" src="C:\Users\dave\Documents\Projects\OSM\Learning_JOSM\Example2E.jpg"></p>
<p>Choices are provided in the dropdowns on the right side of the dialog.  In this case, the names and types differ.  The western end was incorrectly named "Country Road 66", so "County Road 66" was selected.  "Unclassifed" is not one of the choices for highway type, so both were tagged as residential and later changed to "unclassifed".  </p>
<p>At 40.4341579, -104.5078379 the tertiary County Road 59 crosses Crow Creek (not yet mapped).  A highway crossing a waterway requires a bridge, a tunnel or a ford.  To bridge the creek, we will first split the highway into 3 segments and then tag the center section as a bridge.  </p>
<p>There is a handle <strong><em>(+)</em></strong> about 1/4 mile south of the creek that can be selected and dragged to one side of the bridge.  Doing so will create two other handles, one of which can be dragged to the other side.</p>
<p><img alt="Bridge1" src="C:\Users\dave\Documents\Projects\OSM\Learning_JOSM\Bridge1.jpg"></p>
<p>Alternatively, double-clicking the way (while in "Add" mode) will create a new node at the desired location.  Select both nodes (one on each side of the bridge and press the <strong><em>Split A Way...</em></strong> button or press the <strong><em>P</em></strong> key to create a new way over the creek.</p>
<p><img alt="Bridge2" src="C:\Users\dave\Documents\Projects\OSM\Learning_JOSM\Bridge2.jpg"></p>
<p> Select the bridge portion and tag it with <strong><em>bridge = yes</em></strong> and <strong><em>Layer = 1</em></strong>.  The <strong><em>layer</em></strong> tag is used to set the relative elevation.  A tunnel will typically be tagged with <strong><em>layer = -1</em></strong>.  Complex highway interchanges can have several different layers.</p>
<p> <img alt="Bridge3" src="C:\Users\dave\Documents\Projects\OSM\Learning_JOSM\Bridge3.jpg"></p>
<p> Now the stream can be drawn and tagged with <strong><em>waterway = stream</em></strong> and <strong><em>name = Crow Creek</em></strong>.  With the bridge now in place, flooding risk should be minimal and the data can be safely uploaded to OpenStreetMap.</p>
<h2 id="uploading-changes">Uploading Changes</h2>
<p>Changes should be saved to The Map frequently (perhaps after 50-100 edits or so).  Pressing the green up arrow along the top will upload changes, but only after an attempt to validate them.  Errors will have to be fixed.  Warnings should be investigated, but they will not prevent an upload.  Although the validator has found something suspicious, it may actually be intended and correct.  The  <strong><em>Validation Results</em></strong> pane in the lower right can be used to zoom in to any problems.  Be sure the problem object is selected before attempting to fix it.  </p>
<p>Add comments briefly describing your changes and add the image sources you used.</p>
<p><img alt="Upload Dialog" src="C:\Users\dave\Documents\Projects\OSM\Learning_JOSM\Example2F.jpg"></p>
<h2 id="relations">Relations</h2>
<p>Relations are higher-level constructs containing members--different elements with some attribute in common.  See the <a href="https://wiki.openstreetmap.org/wiki/Relation">Wiki Relations</a> page for more information.</p>
<p>An example might be a river.  The edges of the river comprise the outer riverbank and islands.  OSM considers this the "River Area" and can treat it as a relation.  The river also has a main channel and perhaps some smaller channels around islands, also related.</p>
<p>Following the 2013 floods, the South Platte River's course was different from before.  Only some of the changes are reflected in the current OpenStreetMap database.  In this example (the dam is at 40.31776, -104.3761843), the river channel overlaps land, the area of the river does not cover the water, and some islands are not mapped at all.</p>
<p><img alt="South Platte Example" src="C:\Users\dave\Documents\Projects\OSM\Learning_JOSM\SouthPlatte1.jpg"></p>
<p>A closed way (without its own tags) represents the outer riverbank.  The way is part of a relation that defines the river area.  To edit or show the contents of the relation, first make sure the correct entry is highlighted in the relations list.  This can be done by right-clicking the relation in the <strong><em>Tags...</em></strong> window and selecting <strong><em>Show in Relation List</em></strong>.  Click on the notepad/pencil button at the bottom of the relation list to bring up the editor.  The button to its left with the cog and + sign is for creating a new relation.</p>
<p>The edit window shows the attributes and members of the relation.  This one comprises one outer member (the outer river bank) and numerous inner members (islands).</p>
<p><img alt="SouthPlatte2" src="C:\Users\dave\Documents\Projects\OSM\Learning_JOSM\SouthPlatte2.jpg"></p>
<p>Let's edit the river bank to reflect the current state of the South Platte.  According to OSM standards, migrating sand bars should included in the water area.  Vegetation can provide a clue as to whether an island is more or less permanent.  See <a href="https://wiki.openstreetmap.org/wiki/Rivers">Rivers</a> for more information.</p>
<p>The image water area covers a larger area than that shown on the map.  We can move the riverbank nodes around to more closely match.  One way to move the river area further out along the dam is to select these two nodes, the dam node after the other one and press <strong><em>M</em></strong> to merge them.<br><img alt="SouthPlatte3" src="C:\Users\dave\Documents\Projects\OSM\Learning_JOSM\SouthPlatte3.jpg"></p>
<p>Move other nodes to match the riverbank.  Alternatively, split and remove segments and delete and replace them with new segments.  </p>
<p>Delete any islands that no longer are present and add new islands as closed ways.  Smaller islands, say &lt; 1 mile circumference, should be tagged as <strong><em>place = islet</em></strong>.</p>
<p><img alt="SouthPlatte4" src="C:\Users\dave\Documents\Projects\OSM\Learning_JOSM\SouthPlatte4.jpg"></p>
<p>The new islands should be added to the river area multipolygon relation with an inner role.  All currently selected objects are listed in the Relation Editor, so simply pressing the arrow between <strong><em>Members</em></strong> and <strong><em>Selection</em></strong> will add them.  The <strong><em>inner</em></strong> role must be filled in independently.</p>
<p><img alt="SouthPlatte5" src="C:\Users\dave\Documents\Projects\OSM\Learning_JOSM\southPlatte5.jpg"></p>
<p>Upload or discard changes, or save them in a file for later editing, and we're done!</p></body>
      </html>
