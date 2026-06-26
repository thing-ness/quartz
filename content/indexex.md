v1.05
hele koddige bespreking uit NRC over dat ayruveda programma waar ik het over had.
[[Marleen heeft door haar hoge pitta weleens een middelvinger opgestoken in het verkeer]]

---

i managed to hack a way to reduce the 300 pixel margin on the right to 150
by adjusting this
\$sidePanelWidth: 160px; //190px;
in /styles/variables.scss

but i like to have the same 160 pixel margin on the right as on the left (for readability) but i have no idea where to begin. i also like to get rid of the read time thing at the top of each post which is the most idiotic thing i've ever seen mindlessly being copied by everyone on the internet. oh wait.

i tried adding this custom css

`.entry-meta .reading-time {`
`display: none;`
`}`

but it didn't get rid of it.
