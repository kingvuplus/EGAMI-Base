installdir = $(pkglibdir)/python/Plugins/SystemPlugins

SUBDIRS = PositionerSetup Satfinder \
	SkinSelector SatelliteEquipmentControl Videomode VideoTune Hotplug \
	DefaultServicesScanner DiseqcTester CommonInterfaceAssignment \
	CableScan FastScan OSDPositionSetup OSD3DSetup HdmiCEC VideoClippingSetup \
	VideoEnhancement WirelessLan NetworkWizard AnimationSetup

if HAVE_TEMPFANCONTROL
SUBDIRS += TempFanControl
endif

if HAVE_LIBVUGLES2
SUBDIRS += AnimationSetup
endif

install_PYTHON =	\
	__init__.py
