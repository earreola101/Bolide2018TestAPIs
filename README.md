# Bolide2018TestAPIs Edward Arreola
import subprocess
import sys,string,os
import random
from time import sleep
from colorconsole import terminal

API document
# https://docs.google.com/document/d/1Ca1AW4Fv31_qzrmabcdhQMrKTkjqu-xY3QLzWUdTPRw/edit

def class TVHUB
	#table hub commands
	def GetTVHUB_HardwareVersion():
		#returns the hardware version for the PCB type.
		return
		
	def GetTVHUB_FirmwareVersion():
		#returns the sofyware version for the firmware binary.
		return
		
	def GetTVHUB_ValensInitStatus():
		#returns the valens chip successful initialization status.
		return
		
	def GetTVHUB_USBPIDVID():
		#returns the PIDVID from memory in the.
		return
		
	def GetTVHUB_GUID():
		#return the TVHUB GUID unique number.
		return

	def StTVHUB_GUID():
		#writes the TV HUB GUID number.
		return
		
	def SetTVHUB_TestTracking():
		#write the test tracking data buffer.
		return	

	def GetTVHUB_TestTracking():
		#read the test tracking data buffer.
		return
		
	def SetTVHUB_BluetoothMacaddress():
		#write the bluetooth macaddress.
		return
		
	def GetTVHUB_BluetoothMacaddress():
		#read the bluetooth macaddress.
		return	

	def SetTVHUB_DeviceName():
		#write the bluetooth macaddress.
		return	
		
	def GetTVHUB_DeviceName():
		#read the bluetooth macaddress.
		return
		
	def GetTVHUB_Device_Manufacturing_Name():
		#read device manufacturing name.
		return

	def SetTVHUB_Device_Manufacturing_Name():
		#write device manufacturing name.
		return	

	def GetTVHUB_Bluetooth_TX_Frequency():
		#read device Bluetooth_TX_Frequency.
		return		
		
	def SetTVHUB_Bluetooth_TX_Frequency():
		#write device Bluetooth_TX_Frequency.
		return

	def SetTVHUB_USB_HUB_Mode():
		#write device USB HUB Mode.
		return
		
	def GetTVHUB_Speaker_HUB_Connection_Status():
		#read speaker hub connection status
		return
		
	def GetsTVHUB_The_Hub_USB_Cable_Connection_Status():
		#read the hub usb cable connection status.
	   return	
		
	def GetTVHUB_Valens_Connection_Status():
	  #read the tv hub valens connection status.
	  return
  
def class TableHub

	def SetTableHub_SecurityIC_UID():
	#the write the table hub security IC UID.
	return
	
	def SetTableHub_OPT_SecuirtyIC():
	#write the table hub device name.
	return
	
	def GetTableHub_SecurityUID():
	#read security UID.
	return
	
	def SetTableHub_NumOfDev():
	#set TableHub NumOfDev.
    return
	
def class Micpod
	
	def SetMicpodLedControl():
	# set micpod led control
	return
	
	def GetMicpodLedControl():
	#returns the led state.
	return
	
	def SetMicpodReset():
	#send a reset command.
	return
	
	def GetMicpodVersion():
	#returns micpod firmware versions.
	return
	
    def SetMicpodChannel():
	#selects micpod channels
	return
	
	def SetMicpodLoopback():
	# sets the micpod loopback.
	return

def class Splitter
    def SetMicpodSplitterLed():
	#sets the micpod splitter led state.
    return	
	
