# ExoPlayer-Playing-Audio-Video
How to play Video in ExoPlayer – Playing Audio Video

I have created a ExoPlayer Manager You have to call just below code

        PlayerView mPlayerView = findViewById(R.id.mPlayerView);
        mPlayerView.setPlayer(PlayerManager.getSharedInstance(PlayerActivity.this).getPlayerView().getPlayer());
        PlayerManager.getSharedInstance(PlayerActivity.this).playStream(mFilePath);
        PlayerManager.getSharedInstance(this).setPlayerListener(this);
        
        
        Read Full Article 
        https://androidwave.com/how-to-use-exoplayer-playing-audio-video/
