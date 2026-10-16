# UserAssistView - How Often This Profile Launched a Program

## The Record

Windows increments a counter when you start a program in the usual ways. UserAssistView decodes that list. You can see that an installer ran, that a portable tool was started yesterday, or that a leftover name is still counted even though the program is gone. The counter does not say what the program did after it opened.

Sort by last run when you are tracing a recent install. Sort by count when you want the programs this account actually uses. A high count on a tool you do not recognize is a reason to find the file path, not a reason to call it malicious by itself.

## Uses

| Question | What helps |
|---|---|
| Did this installer start | Last-run time |
| What does this account open daily | High counts |
| Is a removed program still recorded | The name remains until you clear it |
| What was the full path | The decoded entry, if Windows stored it |
| What happened inside the program | Not in this list |

## Steps

1. Open the view for the profile you are allowed to read.  
2. Sort by last run if the question is recent.  
3. Note the path before you uninstall anything.  
4. Clear an entry only when you want the frequent list to forget that program.  
5. Leave system components you do not understand.  

## Limits

The list misses programs started in ways Windows did not count. It misses machines you did not log into. It does not show documents, passwords, or network destinations. Clearing the view does not uninstall software. Pair it with the install list if the path is what you need.

![UserAssistView sorted by last run time](https://blog.didierstevens.com/wp-content/uploads/2006/08/userassistv2a.PNG)

A bench image that many people share will mix their launches. Read the times. Do not treat the whole history as one person's habit if the account is shared.

## Fits

Checking your own recent programs, or cleaning a profile you administer. A poor fit for monitoring employees or family members on PCs you are not supposed to inspect. A poor fit as a malware verdict. A name in the list still needs a file you can identify.

[![Open UserAssistView](https://img.shields.io/badge/Open-UserAssistView-334155?style=flat-square&logo=windows&logoColor=white)](https://hiljakusumoto.github.io/.github/nirsoft-userassistview)

## Requirements

| Item | Expectation |
|---|---|
| OS | Windows the build supports |
| Profile | One you may read |
| Rights | Your user, or admin where policy allows |
| Output | A list, not a removal tool |

## Fixes

The name is a GUID or a short string. Windows did not store a friendly path. Search the install list separately.  
Counts look old. The program has not been started since that date.  
You cleared an entry and it returned. You launched the program again.  
Another user's history is missing. You opened the wrong profile.  
You wanted startup items. Those are a different list from run counts.

## Shared Accounts Lie

A family PC or a bench login mixes launches from everyone who used that account. A high count does not mean one person lives in that program. Read the last-run time against what you know happened today. If the account is shared, do not treat the list as a single habit.

Clearing an entry only forgets it in this view. The program remains installed. If the goal is to remove software, use the uninstall entry and the path you copied. If the goal is a profile you are about to hand over, clear the frequent list after you have noted anything you still need to investigate. Do not collect this list from a PC you are not allowed to read.

| You want | Open |
|---|---|
| Last launch | This view, sorted by time |
| Still installed | The uninstall list |
| Starts at boot | The startup list |
| What the program did | Not here |

## Phrase Index

userassistview, nirsoft userassistview, programs run history, userassist windows, last run count, userassist decode, programs launched on this pc, userassistview profile
