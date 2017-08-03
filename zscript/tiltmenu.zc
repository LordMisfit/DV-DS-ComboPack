//===========================================================================
//
// Custom Widgets for Tilt++
// Adds tooltips to widgets
//
// Some redundant duplicates here but whatever; menus are painful to work
// with in general anyway. >:(
//
//===========================================================================

class OptionMenuItemTiltPlusPlusOption : OptionMenuItemOption
{
	String mTooltip;

	OptionMenuItemTiltPlusPlusOption Init(String label, String tooltip, Name command, Name values, CVar graycheck = null, int center = 0)
	{
		mTooltip = tooltip;
		Super.Init(label, command, values, graycheck, center);
		return self;
	}
}

class OptionMenuItemTiltPlusPlusSlider : OptionMenuItemSlider
{
	String mTooltip;

	OptionMenuItemTiltPlusPlusSlider Init(String label, String tooltip, Name command, double min, double max, double step, int showval = 1)
	{
		mTooltip = tooltip;
		Super.Init(label, command, min, max, step, showval);
		return self;
	}
}

//===========================================================================
//
// Tilt++ Menu
//
//===========================================================================

class TiltPlusPlusMenu : OptionMenu
{
	override void Drawer ()
	{
		Super.Drawer();

		String tt;

		if (mDesc.mSelectedItem > 0)
		{
			if (mDesc.mItems[mDesc.mSelectedItem] is "OptionMenuItemTiltPlusPlusOption")
			{
				tt = StringTable.Localize(OptionMenuItemTiltPlusPlusOption(mDesc.mItems[mDesc.mSelectedItem]).mTooltip);
			}

			if (mDesc.mItems[mDesc.mSelectedItem] is "OptionMenuItemTiltPlusPlusSlider")
			{
				tt = StringTable.Localize(OptionMenuItemTiltPlusPlusSlider(mDesc.mItems[mDesc.mSelectedItem]).mTooltip);
			}
		}

		if (tt.Length() > 0)
		{
			screen.DrawText (SmallFont, OptionMenuSettings.mFontColorValue,
				(screen.GetWidth() - SmallFont.StringWidth (tt) * CleanXfac_1) / 2,
				screen.GetHeight() - (SmallFont.GetHeight() * 8),
				tt,
				DTA_CleanNoMove_1, true);
		}
	}
}
