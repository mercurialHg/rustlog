### Before "Hello, World"
For each lesson, try to throw all imaginable exceptions. Befriend the bugs.  
Try to use git to learn. So for a lesson that involves a lot of intentional breaking (marked by a commit) create a branch where you break things.  
"Breaking stuff before making stuff" seems like a good naive philosophy.  
Also, "Erring on the side of caution" feels better if there's no need for caution.   

### "Hello, World!"
cli: `cargo new hello`
1. creates `hello` folder
2. creates stuff inside `hello` folder
3. runs `git init` (nice!)
4. got this in terminal - cargo is quite friendly (thanks, Mozilla!)
```plain
note: see more `Cargo.toml` keys and their definitions at https://doc.rust-lang.org/cargo/reference/manifest.html
```

cli: `cargo run` (but in parent of `hello`)
- error: could not find `Cargo.toml` in directory or parent

cli: `cargo run` (where i should have)
- some important stuff
- "Hello, World!"

cli: `cargo run` (a second time)
- `Compiling` step not present in important stuff
- seems rust knows you havent changed the source code

cli: `cargo run --release`
- this ones different

question: compile without debug symbols (this is for later)

### "Hello again, World!"
Semicolons?: make sure to use them always (and learn about exceptions and special cases later)  
Also, a healthy habit.  

Variables:  
1. immutable by default - helps with safety, concurrency & speed (this is for later)  
2. `let` keyword  
3. type annotation?: healthy habit first (then adapt as you learn) 
4. [leaving this empty for future me]
5. [leaving this empty for future me, too]
6. [one more. I expect learning rust to be a humbling experience, so yeah... Still cool, though!]

Now go and start throwing exceptions.

Constants:
1. `const` keyword
2. naming: SCREAMING_SNAKECASE (convention)
3. type annotation (mandatory!)
4. value: constant expression that can be determined at compile time
5. (future humbling exp 1)
6. (future humbling exp 2)
7. (future humbling exp 3)

Now go and start throwing exceptions (but jucier ones).

