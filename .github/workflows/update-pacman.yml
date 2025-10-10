import datetime

commits_today = datetime.datetime.now().day % 5  # dummy value
svg_template = f"""
<svg viewBox="0 0 120 20" xmlns="http://www.w3.org/2000/svg">
  <circle cx="10" cy="10" r="8" fill="yellow" />
  {"".join([f'<circle cx="{30 + i*20}" cy="10" r="3" fill="white"/>' for i in range(5 - commits_today)])}
</svg>
"""

with open("assets/pacman.svg", "w") as f:
    f.write(svg_template)
