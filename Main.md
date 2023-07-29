- [ ] ok
- [x] not ok

Subjects
- test 1 ello
- test 2
- [[Combinatorial logic]] 
- [[Math Definitions]] 
- ==test==
	- [x] test
	- test
		- test2 test
- not end
	- indent

this i meant to be a normal paragraph.
lets see.  
if it works

# h1
## h2
**bold** bold
*italic*
~~strike~~
1. [ ] Do first step
2. [ ] Do next step
3. [x] Do following step
	1. [ ] test2
		1. [ ] test3

```css
* {
  background-color: white;
}
```

a very long string|almost as long|very long
--:|:--:|:--
d|e|f
g|h|i

```mermaid
sequenceDiagram
    actor A1
    participant B1
    A1->>B1: Hello John, how are you?
    A1->>B1: John, can you hear me?
    A1->>C1: hello
    B1->>C1: hello
    B1->>A1: Hi Alice, I can hear you!
    Note over A1,B1: A typical interaction
    B1->>A1: I feel great!
    loop Every minute
        B1->>C1: Great!
    end
    A1->>A1: tf am i doing
    A1->>B1: done
```

```mermaid
flowchart TD
    A[Start] --> B{Is it?}
    B -->|Yes| C[OK]
    C --> D[Rethink]
    D --> B
    B ---->|No| E[End]
```
```mermaid
gitGraph
       commit id: "1"
       commit id: "2"
       branch nice_feature
       checkout nice_feature
       commit id: "3"
       checkout main
       commit id: "4"
       checkout nice_feature
       branch very_nice_feature
       checkout very_nice_feature
       commit id: "5"
       checkout main
       commit id: "6"
       checkout nice_feature
       commit id: "7"
       checkout main
       merge nice_feature id: "customID" tag: "customTag" type: REVERSE
       checkout very_nice_feature
       commit id: "8"
       checkout main
       commit id: "9"
```