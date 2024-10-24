# Welcome to My GitHub Profile

Hello! I'm **snowdev** (also known as **thesondev** or **Tdv**), a **Freelance Developer**. Below is a little snippet about me, written in Go:

```go
package main

import (
    "snow"
    "github.com/phamtheson2807"
)

type Github struct {
    username        string
    contacts        map[string]string
    alises          []string
    location        string
    age             string
    occupation      string
    operating_system string
}

func (g *Github) Init() {
    g.username = "snowdev"
    g.contacts = map[string]string{
        "Discord":  "#",
        "Facebook": "PhamTheSon.User",
    }
    g.alises = []string{"thesondev", "Tdv"}
    g.location = "localhost, vietnamese"
    g.age = "21+"
    g.occupation = "Freelance Developer"
    g.operating_system = "Windows, Arch, Linux, VPS"
}
