# Super-Monk
A Mod that lets you fly around in Modded Lobbies
# How to use Super Monk
1. Download mod
2. Go in modded lobby
3. Click "A" on your right controller to fly
4. Wherever your head is looking at you will go in that direction
# Requirments
Utilla (Only requirement!)
# My code if you want to use it in your mod
No need to give credits for my code because yeah i dont mind anyways here is my code:



if (ControllerInputPoller.instance.rightControllerPrimaryButton)
{
    GorillaLocomotion.Player.Instance.GetComponent<Rigidbody>().velocity = GorillaLocomotion.Player.Instance.headCollider.transform.forward * Time.deltaTime * 15f;
}



yaaaa here it is
