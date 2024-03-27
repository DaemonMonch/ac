- usage
  
      trie := NewTrie()
      trie.AddKeyword("ac")
      trie.AddKeyword("de")
      emits := trie.ParseText("acde") //emits is a list of matched keyword with start and end offset in parse text 

   
