package botwars.main;

import android.app.Activity;
import android.os.Bundle;

import android.content.Context;
import android.content.Intent;
import android.content.pm.ActivityInfo;
import android.view.KeyEvent;
import android.view.View;
import android.view.ViewGroup;
import android.widget.AdapterView;
import android.widget.AdapterView.OnItemClickListener;
import android.widget.BaseAdapter;
import android.widget.GridView;
import android.widget.ImageView;
import android.widget.Toast;

public class MapMenu extends Activity {

	

	/** Called when the activity is first created. */
	@Override////////asdd
	public void onCreate(Bundle savedInstanceState) {
		super.onCreate(savedInstanceState);
		setRequestedOrientation(ActivityInfo.SCREEN_ORIENTATION_LANDSCAPE);
		setContentView(R.layout.mapmenu);
		GridView gridView = (GridView) findViewById(R.id.gridview);
		gridView.setOnItemClickListener(new OnItemClickListener() {
			public void onItemClick(AdapterView<?> parent, View v,
					int position, long id) {////
					BotWars.setMap(0);
					Intent StartIntent = new Intent(MapMenu.this, BotWars.class);
					startActivity(StartIntent);
					finish();

			}
		});
	}




}