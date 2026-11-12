Roman society exercise: 
- I ran into an error in the google collab workbook, in cell 10, saying "name 'networkx' is not defined". Thankfully the fix was simple, and Gemini was able to fix it: The error happens because the networkx library was imported using the nickname nx in your setup block (import networkx as nx). Because of this, Python doesn't recognize the full name networkx when you try to call it.

To fix the error, you just need to change networkx.degree(G) to nx.degree(G). I have updated the cell with this fix. - easy fix and I can continue the workbook

- Ran into the same issue in Cell 15
