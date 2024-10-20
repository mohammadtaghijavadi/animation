import animation 

# Set the hidden passcode
passcode = "800808"
def set_passcode():
    animation.set_passcode(passcode)

#Function to run the passcoce animation
def run_animation():
    try:
        animation.run()
    except:
        print()

#Run the animation
run_animation()
