# Metaverse

```json
{
  "api_version": "1.0",
  "base_url": "https://api.metaversecourse.com/v1",
  "authentication": {
    "method": "API Key",
    "header": "Authorization: Bearer {API_KEY}"
  },
  "response_format": {
    "success": {
      "status": "success",
      "data": {}
    },
    "error": {
      "status": "error",
      "message": "Error description here"
    }
  },
  "teams": {
    "team2": {
      "project": "Solaris (Rocket)",
      "endpoints": {
        "status": "/team2/status",
        "control": "/team2/control"
      },
      "actions": ["launch", "detach_booster", "activate_claw"]
    },
    "team3": {
      "project": "Healthcare Warehouse",
      "endpoints": {
        "status": "/team3/status",
        "control": "/team3/control"
      },
      "actions": ["move_robot", "start_operation", "stop_operation"]
    },
    "team4": {
      "project": "Tunnel Rover",
      "endpoints": {
        "status": "/team4/status",
        "control": "/team4/control"
      },
      "actions": ["move_rover", "deliver_relief_material"]
    },
    "team5": {
      "project": "EEG Brain Simulation",
      "endpoints": {
        "data": "/team5/data",
        "control": "/team5/control"
      },
      "actions": ["simulate_activity", "move_robot", "update_brain_state"]
    },
    "team6": {
      "project": "Gravity Battery",
      "endpoints": {
        "status": "/team6/status",
        "control": "/team6/control"
      },
      "actions": ["lift_weight", "generate_electricity"]
    },
    "team7": {
      "project": "FearTherapy VR",
      "endpoints": {
        "session": "/team7/session",
        "control": "/team7/control"
      },
      "actions": ["start_session", "end_session", "adjust_difficulty"]
    },
    "team8": {
      "project": "Digital Heart Pulse and Blood Flow",
      "endpoints": {
        "data": "/team8/data",
        "control": "/team8/control"
      },
      "actions": ["trigger_alert", "send_calming_message"]
    },
    "team9": {
      "project": "EarthTwin",
      "endpoints": {
        "data": "/team9/data",
        "control": "/team9/control"
      },
      "actions": ["update_simulation_parameters"]
    },
    "team10": {
      "project": "Remote Surgery Robotic Arm",
      "endpoints": {
        "status": "/team10/status",
        "control": "/team10/control"
      },
      "actions": ["move_stitching_hand", "move_hook_hand", "perform_surgical_action"]
    },
    "team11": {
      "project": "Smart E Yantra Room",
      "endpoints": {
        "status": "/team11/status",
        "control": "/team11/control"
      },
      "actions": ["toggle_light", "toggle_fan", "lock_door", "unlock_door", "heat_alert"]
    },
    "team12": {
      "project": "AI-Based Posture Correction",
      "endpoints": {
        "data": "/team12/data",
        "control": "/team12/control"
      },
      "actions": ["calibrate_sensors", "update_arm_position"]
    },
    "team13": {
      "project": "Rescue Twin Rover",
      "endpoints": {
        "status": "/team13/status",
        "control": "/team13/control"
      },
      "actions": ["navigate_rover", "activate_sensors"]
    },
    "team15": {
      "project": "Metal Detection Rover",
      "endpoints": {
        "status": "/team15/status",
        "control": "/team15/control"
      },
      "actions": ["move_rover", "scan_terrain"]
    },
    "team16": {
      "project": "ICU Ventilator Control System",
      "endpoints": {
        "status": "/team16/status",
        "control": "/team16/control"
      },
      "actions": ["adjust_settings", "sync_unity_model"]
    }
  }
}
