home
====
touch README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/Love-Perfume/home.git
git push -u origin master
function __doRange( $arr ) {
		$newarr = array();
		if ( is_array($arr) && count($arr)>0 ) {
			foreach ($arr as $k => $v) {
				$newarr[ $v ] = $v;
			}
		}
		return $newarr;
	}
		
	function psp_wplanner_fb_options() 
	{
		global $wpdb, $psp;
		
		/* Here we define the different drop downs for our option page */
		
		// Facebook language
		$select_fblanguage = array( "af_ZA" => "Afrikaans","sq_AL" => "Albanian","ar_AR" => "Arabic","hy_AM" => "Armenian","eu_ES" => "Basque","be_BY" => "Belarusian","bn_IN" => "Bengali","bs_BA" => "Bosanski","bg_BG" => "Bulgarian","ca_ES" => "Catalan","zh_CN" => "Chinese","cs_CZ" => "Czech","da_DK" => "Danish","fy_NL" => "Dutch","en_US" => "English","eo_EO" => "Esperanto","et_EE" => "Estonian","et_EE" => "Estonian","fi_FI" => "Finnish","fo_FO" => "Faroese","tl_PH" => "Filipino","fr_FR" => "French","gl_ES" => "Galician","ka_GE" => "Georgian","de_DE" => "German","zh_CN" => "Greek","he_IL" => "Hebrew","hi_IN" => "Hindi","hr_HR" => "Hrvatski","hu_HU" => "Hungarian","is_IS" => "Icelandic","id_ID" => "Indonesian","ga_IE" => "Irish","it_IT" => "Italian","ja_JP" => "Japanese","ko_KR" => "Korean","ku_TR" => "Kurdish","la_VA" => "Latin","lv_LV" => "Latvian","fb_LT" => "Leet Speak","lt_LT" => "Lithuanian","mk_MK" => "Macedonian","ms_MY" => "Malay","ml_IN" => "Malayalam","nl_NL" => "Nederlands","ne_NP" => "Nepali","nb_NO" => "Norwegian","ps_AF" => "Pashto","fa_IR" => "Persian","pl_PL" => "Polish","pt_PT" => "Portugese","pa_IN" => "Punjabi","ro_RO" => "Romanian","ru_RU" => "Russian","sk_SK" => "Slovak","sl_SI" => "Slovenian","es_LA" => "Spanish","sr_RS" => "Srpski","sw_KE" => "Swahili","sv_SE" => "Swedish","ta_IN" => "Tamil","te_IN" => "Telugu","th_TH" => "Thai","tr_TR" => "Turkish","uk_UA" => "Ukrainian","vi_VN" => "Viettitlese","cy_GB" => "Welsh" );
