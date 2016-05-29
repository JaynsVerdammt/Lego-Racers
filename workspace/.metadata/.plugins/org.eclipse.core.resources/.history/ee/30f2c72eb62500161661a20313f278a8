package sensors;

import controller.MainControl;
import lejos.nxt.ColorSensor;
import lejos.nxt.SensorPort;
import lejos.robotics.Color;

public class RGBControl extends Thread{
	
	public static final int BLACK = Color.BLACK;
	public static final int WHITE = Color.WHITE;
	public static final int RED = Color.RED;
	public static final int GREEN = Color.GREEN;
	
	public RGBControl(MainControl mainControl) {
		// TODO Auto-generated constructor stub
	}
	
	public int getColor() {
		ColorSensor colorSensor = new ColorSensor(SensorPort.S1);
		colorSensor.getColorID();
		
		return colorSensor.getColorID();
	}

}
