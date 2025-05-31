+++
title = "{{ replace .Name "-" " " | title }}"
date = "{{ .Date }}"

#
# Set menu to "main" to add this page to
# the main menu on top of the page
#
menu = "main"

#
# description is optional
#
# description = "An optional description for SEO. If not provided, an automatically created summary will be used."

#
# tags are optional
#
# tags = [{{ range $plural, $terms := .Site.Taxonomies }}{{ range $term, $val := $terms }}"{{ printf "%s" $term }}",{{ end }}{{ end }}]
+++

Hi! I am a current Economics and Mathematics BA candidate at Amherst College. I am also research assistant at Harvard Law School's Center for Labor and a Just Economy, under the supervision of Prof. Richard Freeman, and at Columbia University's Teachers College, under the supervision of Prof. Kirsten Sluungard Mumma.  My current research focus is Labor Economics and Education Economics.

You can reach me via email at opolachini26@amherst.edu.

This is a page about »{{ replace .Name "-" " " | title }}«.
