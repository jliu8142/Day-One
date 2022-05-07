# Day-One
void Game : :RunLoop ()
{
    while (!mShouldQuit)
    {
       // Process Inputs
       JoystickData j = GetJoystickData () ;
       
       
       // Update Game World 
       UpdatePlayerPoition (j) ;
       
       
       for (Ghost& g : mGhost)
       {
          if (g. Collides (player))
          }
          else
          {
             g.Update();
          }
       }
       
       //Handle Pac-Man eating pellets
       // ...
       
       // Generate Outputs
       RenderGraphics();
       RenderAudio();
       }
   }
