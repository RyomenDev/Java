# Set Up Your Development Environment

## ✅ Step 1: Check if JDK is installed

Open a new terminal (PowerShell or Command Prompt).

Run:

```bash
java -version
javac -version
```

- If java works but javac doesn't, it means **only the JRE is installed**, not the JDK.
- If neither works, you need to **install the JDK**.

## ✅ Step 2: Install the JDK (if not installed)

- Download and install the latest JDK from the official Oracle page or OpenJDK.

## ✅ Step 3: Add JDK to System PATH

- Press `Win + S`, type **Environment Variables**, and open "Edit the system environment variables".
- In the **System Properties** window, click on **Environment Variables**.
- Under **System Variables**, find the Path variable, and click **Edit**.
- Add a new entry pointing to the JDK's bin folder. For example:

```makefile
C:\Program Files\Java\jdk-21\bin
```

- Click OK to close all windows.

## ✅ Step 4: Verify

- Close and reopen your terminal, then run:
- Restart Everything : Close and reopen your terminal,IDE (or ideally, restart your PC).

#### Manually Test in Terminal
```
& "C:\Program Files\Java\jdk-24\bin\javac.exe" -version
```

```bash
javac -version
```

You should now see the Java compiler version.
