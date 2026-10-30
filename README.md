# Hi, I'm hml7! 👋

A developer based in Poland who loves building open-source tools and experimenting with low-level & system languages.

```nim
# quick_info.nim
type Developer = object
  location: string
  focus: string
  learning: seq[string]

let me = Developer(
  location: "Poland",
  focus: "Open Source & Software Engineering",
  learning: @["Nim", "C", "Lua"]
)

echo "Building practical tools and exploring neat architectures."
