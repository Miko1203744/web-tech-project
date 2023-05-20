# css selector

Date Created: May 19, 2023 9:38 PM

# 

# CSS Selectors

In CSS, selectors are patterns used to select the element(s) you want to style.

Use our [CSS Selector Tester](https://www.w3schools.com/cssref/trysel.php) to demonstrate the different selectors.

| Selector | Example | Example description |
| --- | --- | --- |
| https://www.w3schools.com/cssref/sel_class.phphttps://www.w3schools.com/cssref/sel_class.php | .intro | Selects all elements with class="intro" |
| .class1.class2 | .name1.name2 | Selects all elements with both name1 and name2 set within its class attribute |
| .class1 .class2 | .name1 .name2 | Selects all elements with name2 that is a descendant of an element with name1 |
| https://www.w3schools.com/cssref/sel_id.phphttps://www.w3schools.com/cssref/sel_id.php | #firstname | Selects the element with id="firstname" |
| https://www.w3schools.com/cssref/sel_all.php | * | Selects all elements |
| https://www.w3schools.com/cssref/sel_element.php | p | Selects all <p> elements |
| https://www.w3schools.com/cssref/sel_element_class.php | p.intro | Selects all <p> elements with class="intro" |
| https://www.w3schools.com/cssref/sel_element_comma.php | div, p | Selects all <div> elements and all <p> elements |
| https://www.w3schools.com/cssref/sel_element_element.phphttps://www.w3schools.com/cssref/sel_element_element.phphttps://www.w3schools.com/cssref/sel_element_element.php | div p | Selects all <p> elements inside <div> elements |
| https://www.w3schools.com/cssref/sel_element_gt.phphttps://www.w3schools.com/cssref/sel_element_gt.phphttps://www.w3schools.com/cssref/sel_element_gt.php | div > p | Selects all <p> elements where the parent is a <div> element |
| https://www.w3schools.com/cssref/sel_element_pluss.phphttps://www.w3schools.com/cssref/sel_element_pluss.phphttps://www.w3schools.com/cssref/sel_element_pluss.php | div + p | Selects the first <p> element that is placed immediately after <div> elements |
| https://www.w3schools.com/cssref/sel_gen_sibling.phphttps://www.w3schools.com/cssref/sel_gen_sibling.phphttps://www.w3schools.com/cssref/sel_gen_sibling.php | p ~ ul | Selects every <ul> element that is preceded by a <p> element |
| https://www.w3schools.com/cssref/sel_attribute.phphttps://www.w3schools.com/cssref/sel_attribute.phphttps://www.w3schools.com/cssref/sel_attribute.php | [target] | Selects all elements with a target attribute |
| https://www.w3schools.com/cssref/sel_attribute_value.phphttps://www.w3schools.com/cssref/sel_attribute_value.phphttps://www.w3schools.com/cssref/sel_attribute_value.phphttps://www.w3schools.com/cssref/sel_attribute_value.phphttps://www.w3schools.com/cssref/sel_attribute_value.php | [target="_blank"] | Selects all elements with target="_blank" |
| https://www.w3schools.com/cssref/sel_attribute_value_contains.phphttps://www.w3schools.com/cssref/sel_attribute_value_contains.phphttps://www.w3schools.com/cssref/sel_attribute_value_contains.phphttps://www.w3schools.com/cssref/sel_attribute_value_contains.phphttps://www.w3schools.com/cssref/sel_attribute_value_contains.php | [title~="flower"] | Selects all elements with a title attribute containing the word "flower" |
| https://www.w3schools.com/cssref/sel_attribute_value_lang.phphttps://www.w3schools.com/cssref/sel_attribute_value_lang.phphttps://www.w3schools.com/cssref/sel_attribute_value_lang.phphttps://www.w3schools.com/cssref/sel_attribute_value_lang.phphttps://www.w3schools.com/cssref/sel_attribute_value_lang.php | [lang|="en"] | Selects all elements with a lang attribute value equal to "en" or starting with "en-" |
| https://www.w3schools.com/cssref/sel_attr_begin.phphttps://www.w3schools.com/cssref/sel_attr_begin.phphttps://www.w3schools.com/cssref/sel_attr_begin.phphttps://www.w3schools.com/cssref/sel_attr_begin.phphttps://www.w3schools.com/cssref/sel_attr_begin.php | a[href^="https"] | Selects every <a> element whose href attribute value begins with "https" |
| https://www.w3schools.com/cssref/sel_attr_end.phphttps://www.w3schools.com/cssref/sel_attr_end.phphttps://www.w3schools.com/cssref/sel_attr_end.phphttps://www.w3schools.com/cssref/sel_attr_end.phphttps://www.w3schools.com/cssref/sel_attr_end.php | a[href$=".pdf"] | Selects every <a> element whose href attribute value ends with ".pdf" |
| https://www.w3schools.com/cssref/sel_attr_contain.phphttps://www.w3schools.com/cssref/sel_attr_contain.phphttps://www.w3schools.com/cssref/sel_attr_contain.phphttps://www.w3schools.com/cssref/sel_attr_contain.phphttps://www.w3schools.com/cssref/sel_attr_contain.php | a[href*="w3schools"] | Selects every <a> element whose href attribute value contains the substring "w3schools" |
| https://www.w3schools.com/cssref/sel_active.php | a:active | Selects the active link |
| https://www.w3schools.com/cssref/sel_after.php | p::after | Insert something after the content of each <p> element |
| https://www.w3schools.com/cssref/sel_before.php | p::before | Insert something before the content of each <p> element |
| https://www.w3schools.com/cssref/sel_checked.php | input:checked | Selects every checked <input> element |
| https://www.w3schools.com/cssref/sel_default.php | input:default | Selects the default <input> element |
| https://www.w3schools.com/cssref/sel_disabled.php | input:disabled | Selects every disabled <input> element |
| https://www.w3schools.com/cssref/sel_empty.php | p:empty | Selects every <p> element that has no children (including text nodes) |
| https://www.w3schools.com/cssref/sel_enabled.php | input:enabled | Selects every enabled <input> element |
| https://www.w3schools.com/cssref/sel_firstchild.php | p:first-child | Selects every <p> element that is the first child of its parent |
| https://www.w3schools.com/cssref/sel_firstletter.php | p::first-letter | Selects the first letter of every <p> element |
| https://www.w3schools.com/cssref/sel_firstline.php | p::first-line | Selects the first line of every <p> element |
| https://www.w3schools.com/cssref/sel_first-of-type.php | p:first-of-type | Selects every <p> element that is the first <p> element of its parent |
| https://www.w3schools.com/cssref/sel_focus.php | input:focus | Selects the input element which has focus |
| https://www.w3schools.com/cssref/sel_fullscreen.php | :fullscreen | Selects the element that is in full-screen mode |
| https://www.w3schools.com/cssref/sel_hover.php | a:hover | Selects links on mouse over |
| https://www.w3schools.com/cssref/sel_in-range.php | input:in-range | Selects input elements with a value within a specified range |
| https://www.w3schools.com/cssref/sel_indeterminate.php | input:indeterminate | Selects input elements that are in an indeterminate state |
| https://www.w3schools.com/cssref/sel_invalid.php | input:invalid | Selects all input elements with an invalid value |
| https://www.w3schools.com/cssref/sel_lang.phphttps://www.w3schools.com/cssref/sel_lang.phphttps://www.w3schools.com/cssref/sel_lang.php | p:lang(it) | Selects every <p> element with a lang attribute equal to "it" (Italian) |
| https://www.w3schools.com/cssref/sel_last-child.php | p:last-child | Selects every <p> element that is the last child of its parent |
| https://www.w3schools.com/cssref/sel_last-of-type.php | p:last-of-type | Selects every <p> element that is the last <p> element of its parent |
| https://www.w3schools.com/cssref/sel_link.php | a:link | Selects all unvisited links |
| https://www.w3schools.com/cssref/sel_marker.php | ::marker | Selects the markers of list items |
| https://www.w3schools.com/cssref/sel_not.phphttps://www.w3schools.com/cssref/sel_not.phphttps://www.w3schools.com/cssref/sel_not.php | :not(p) | Selects every element that is not a <p> element |
| https://www.w3schools.com/cssref/sel_nth-child.phphttps://www.w3schools.com/cssref/sel_nth-child.phphttps://www.w3schools.com/cssref/sel_nth-child.php | p:nth-child(2) | Selects every <p> element that is the second child of its parent |
| https://www.w3schools.com/cssref/sel_nth-last-child.phphttps://www.w3schools.com/cssref/sel_nth-last-child.phphttps://www.w3schools.com/cssref/sel_nth-last-child.php | p:nth-last-child(2) | Selects every <p> element that is the second child of its parent, counting from the last child |
| https://www.w3schools.com/cssref/sel_nth-last-of-type.phphttps://www.w3schools.com/cssref/sel_nth-last-of-type.phphttps://www.w3schools.com/cssref/sel_nth-last-of-type.php | p:nth-last-of-type(2) | Selects every <p> element that is the second <p> element of its parent, counting from the last child |
| https://www.w3schools.com/cssref/sel_nth-of-type.phphttps://www.w3schools.com/cssref/sel_nth-of-type.phphttps://www.w3schools.com/cssref/sel_nth-of-type.php | p:nth-of-type(2) | Selects every <p> element that is the second <p> element of its parent |
| https://www.w3schools.com/cssref/sel_only-of-type.php | p:only-of-type | Selects every <p> element that is the only <p> element of its parent |
| https://www.w3schools.com/cssref/sel_only-child.php | p:only-child | Selects every <p> element that is the only child of its parent |
| https://www.w3schools.com/cssref/sel_optional.php | input:optional | Selects input elements with no "required" attribute |
| https://www.w3schools.com/cssref/sel_out-of-range.php | input:out-of-range | Selects input elements with a value outside a specified range |
| https://www.w3schools.com/cssref/sel_placeholder.php | input::placeholder | Selects input elements with the "placeholder" attribute specified |
| https://www.w3schools.com/cssref/sel_read-only.php | input:read-only | Selects input elements with the "readonly" attribute specified |
| https://www.w3schools.com/cssref/sel_read-write.php | input:read-write | Selects input elements with the "readonly" attribute NOT specified |
| https://www.w3schools.com/cssref/sel_required.php | input:required | Selects input elements with the "required" attribute specified |
| https://www.w3schools.com/cssref/sel_root.php | :root | Selects the document's root element |
| https://www.w3schools.com/cssref/sel_selection.php | ::selection | Selects the portion of an element that is selected by a user |
| https://www.w3schools.com/cssref/sel_target.php | #news:target | Selects the current active #news element (clicked on a URL containing that anchor name) |
| https://www.w3schools.com/cssref/sel_valid.php | input:valid | Selects all input elements with a valid value |
| https://www.w3schools.com/cssref/sel_visited.php | a:visited | Selects all visited links |
