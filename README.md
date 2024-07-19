This Repo contains fixes for Blue Screen of Death due to CrowdStrike sensor update! Use these workarounds at your own discretion. It involves simple as well as complex solutions!


CrowdStrike Official Workaround

  Boot Windows into Safe Mode or the Windows Recovery Environment
  
  Navigate to the C:\Windows\System32\drivers\CrowdStrike directory
  
  Locate the file matching “C-00000291*.sys”, and delete it.
  
  Boot the host normally.
