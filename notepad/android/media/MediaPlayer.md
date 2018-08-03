# MediaPlayer

## create

MediaPlayer mediaPlayer = MediaPlayer.create(getContext(), R.raw.sound);

MediaPlayer mediaPlayer = MediaPlayer.create(getContext(), Uri.parse("android.resource://com.hatsune.eagleee/raw/sound"));

MediaPlayer mediaPlayer = MediaPlayer.create(getContext(), getResources().getIdentifier("sound", "raw", getActivity().getPackageName()));