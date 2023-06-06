# Text2juliaRegExp
(Audio)Text -> julia RegExp

record audio -> transribe to text -> anything following the keyword "re" -> look for longest matching existing regular expression in the existing code library (base julia plus any new code added)

e.g.

"please run re save underscore picture open parenthesis x close parenthesis and then make the picture black and white" -> 
"please run save_picture(x) and then make the picture black and white" -> give to transformer to create code using the specific function we want it to use
